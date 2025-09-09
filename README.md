# raw json files

A simple, modern, and stylish static web app to browse, view, and share all public JSON files in this directory.

## Features
- Automatically lists all JSON files in the directory (with fallback for static hosting)
- View JSON content in a pretty, collapsible card
- Copy or share direct raw URLs for each file
- Responsive, mobile-friendly, and Bootstrap-styled
- SEO meta tags and favicon support
- Developer and copyright footer

## Usage
1. Place your `.json` files in the same directory as `index.html`.
2. Open `index.html` in your browser, or serve the folder with a static server (e.g. VS Code Live Server).
3. Click "View" to see the JSON, or use "Raw URL"/"Copy URL" to share.

## Customization
- To add or remove files, update the fallback list in the script if your server does not support directory listing.
- Replace `favicon.png` with your own icon for branding.
- Edit the footer for your name and link.

## Example
![screenshot](screenshot.png)

## License
MIT
