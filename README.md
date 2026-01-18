# High Value Trade Tables

A simple, client-side web application for managing High Value Trade Tables to track sales negotiations and exchanges with customers.

## Features

- **Create Multiple Tables**: Create and manage multiple trade tables for different deals
- **Track Gives & Gets**: Organize what you're giving and what you're getting from customers
- **Point System**: Automatically tracks points (1-20) based on row order
- **Checkbox Labels**: Add custom labels to checkboxes when marking completed items
- **Visual Chart**: Real-time bar chart showing Total Gives vs Total Gets points
- **Status Indicator**: See if your deal is Balanced, Unbalanced, or Poor based on point differences
- **Edit Items**: Edit all items by points in a dedicated edit tab
- **Import/Export**: Export tables as JSON files and import them back
- **Share Links**: Share view-only links to your tables
- **Auto-Save**: All changes are automatically saved to browser localStorage

## Getting Started

### Running Locally

1. Simply open `home.html` in your web browser
2. No installation or setup required - everything runs client-side
3. Data is stored in your browser's localStorage

### Creating a Table

1. Enter a name for your table in the input field
2. Click "Create Table"
3. The table opens automatically

### Using Your Table

**View Table Tab:**
- Check/uncheck items to mark completed trades
- Click checkboxes on the "Gets" column (right side) to add custom labels via popup
- View the summary chart and status indicator on the right
- Edit table name at the top

**Edit Items Tab:**
- Edit all item text by points (1-20)
- Use the grid interface to modify "Gives" and "Gets" items
- Click "Save All Changes" when done

### Import/Export

- **Export**: Click "Export" on any table card or "Export All Tables" to save as JSON
- **Import**: Use "Import Tables" to load previously exported tables
- All data including custom text and checkbox labels are preserved

### Sharing Tables

1. Open a table
2. Click "Share Link" in the header
3. Copy the link to share (view-only mode for recipients)

## File Structure

```
.
├── home.html          # Home page with table list
├── index.html         # Main table editor page
└── netlify.toml       # Static hosting configuration (optional)
```

## Data Storage

All data is stored locally in your browser's `localStorage`. This means:
- No server required
- Data persists between sessions
- No account needed
- Privacy-focused (data stays in your browser)

## Browser Compatibility

Works in all modern browsers that support:
- HTML5
- CSS3
- JavaScript (ES6+)
- localStorage API

## Deployment

This is a static site and can be deployed to any static hosting service:
- Netlify
- GitHub Pages
- Vercel
- Any web server

Simply upload the HTML files and they'll work as-is.

## Color Scheme

The application uses a Sales Gauge inspired color scheme:
- **Teal** (`#5AB4B4`) - Primary background and accents
- **Orange** (`#FF9800`) - Buttons and highlights
- **Green** (`#70C040`) - Chart bars and success indicators

## License

ISC

