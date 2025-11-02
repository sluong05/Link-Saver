# Link Saver - Browser Extension

A lightweight browser extension that helps you quickly save and organize links for easy access later.

## Overview

Link Saver is a simple yet effective Chrome/Edge extension that allows you to save URLs with a single click. All saved links are displayed in an organized list within the extension popup, making it easy to revisit your bookmarked pages.

## Features

- **Quick Link Saving**: Save any URL by typing or pasting it into the input field
- **Instant Access**: View all your saved links in a clean, organized list
- **One-Click Navigation**: Click any saved link to open it in a new tab
- **Minimal Design**: Clean, distraction-free interface with a green color scheme
- **Lightweight**: No unnecessary features or bloat

## Installation

### Chrome/Edge

1. Clone or download this repository
2. Open Chrome/Edge and navigate to `chrome://extensions/` (or `edge://extensions/`)
3. Enable "Developer mode" in the top right corner
4. Click "Load unpacked"
5. Select the `Link Saver` folder
6. The extension icon should now appear in your browser toolbar

## Usage

1. Click the extension icon in your browser toolbar to open the popup
2. Enter a URL in the input field
3. Click the "SAVE INPUT" button to save the link
4. Your saved links will appear below in a list
5. Click any link to open it in a new tab

## Tech Stack

- **HTML5**: Structure
- **CSS3**: Styling
- **Vanilla JavaScript**: Functionality
- **Chrome Extension Manifest V3**: Browser extension framework

## File Structure

```
Link Saver/
├── index.html       # Extension popup interface
├── index.js         # Core functionality and link management
├── index.css        # Styling and layout
├── manifest.json    # Extension configuration
├── icon.png         # Extension icon
└── README.md        # Documentation
```

## How It Works

The extension uses vanilla JavaScript to:
- Capture user input from the text field
- Store links in a JavaScript array
- Dynamically render saved links as clickable list items
- Open links in new browser tabs when clicked

## Browser Compatibility

- Chrome (Manifest V3 compatible)
- Edge (Manifest V3 compatible)
- Other Chromium-based browsers

## Future Enhancements

Potential features for future versions:
- Local storage persistence (links survive browser restarts)
- Delete individual links
- Clear all links functionality
- Save current tab URL with one click
- Link categorization/folders
- Search and filter functionality
- Export/import links

## License

This is a practice project for learning web development and browser extension creation.

## Version

Current Version: 1.1
