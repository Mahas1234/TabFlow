# TabFlow AI - Smart Contextual Tab Organizer

TabFlow AI is a Chrome extension that helps you manage your browser tabs intelligently using AI-powered categorization and organization.

## Features

- **Auto-Grouping with Context Awareness**: Automatically categorizes tabs into Work, Research, Social, and Entertainment groups
- **Smart Recommendations**: Suggests closing inactive tabs and maintains a "Revisit Later" list
- **AI-Powered Search**: Search through your tabs using natural language (basic implementation)
- **Tab Timeline**: Tracks tab interactions and usage patterns
- **Minimalist UI**: Clean, intuitive interface that doesn't get in your way

## Installation

1. Clone this repository or download the source code
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable "Developer mode" in the top right corner
4. Click "Load unpacked" and select the extension directory

## Usage

1. Click the TabFlow AI icon in your Chrome toolbar to open the popup
2. Your tabs will be automatically categorized into different groups
3. Use the search bar to find specific tabs
4. Inactive but important tabs will be automatically added to the "Revisit Later" section

## Development

The extension is built using:
- Manifest V3
- Vanilla JavaScript
- Chrome Extension APIs

### Project Structure

```
├── manifest.json      # Extension manifest
├── popup.html        # Main popup interface
├── popup.js         # Popup logic
├── styles.css       # Styling
├── background.js    # Background service worker
└── icons/          # Extension icons
```

## Future Enhancements

- Implement machine learning for better tab categorization
- Add customizable categorization rules
- Integrate with cloud services for sync across devices
- Add tab analytics and insights
- Implement advanced semantic search
# TabFlow
