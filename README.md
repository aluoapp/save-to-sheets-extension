# Save to Sheets Chrome Extension

A Chrome extension built with the Plasmo framework that allows you to easily save web content to Google Sheets. Features include automatic web content matching, multiple sheet configurations, and quick save via context menu.

## Key Features

### 1. Automatic Web Content Matching
- Automatically matches email addresses, links, and image URLs
- Configurable automatic matching and append mode
- Supports saving page title, URL, and domain information
- Preview matched results in table format with copy functionality

### 2. Google Sheets Integration
- Configure multiple Google Sheets destinations
- Select specific sheets and columns
- Custom save configuration names
- Sort and search saved configurations

### 3. Quick Save via Context Menu
- Configurable context menu visibility
- Save selected text or complete page information
- Custom context menu display names
- Configure multiple save destinations

### 4. Sidebar Configuration Panel
- Intuitive Google Sheets authorization management
- Easy sheet and column selection
- Manage and edit saved configurations
- Configure automatic matching rules

## Tech Stack

- Plasmo Framework
- React 18
- TypeScript
- TailwindCSS
- Google Sheets API
- Chrome Extension APIs

## Requirements

- Node.js 16+
- pnpm or npm
- Google Cloud project (with Sheets API enabled)
- Chrome browser

## Quick Start

1. Clone the project

```bash
git clone https://github.com/aluoapp/save-to-sheets-extension.git
cd save-to-sheets-extension
```

2. Install dependencies

```bash
pnpm install
```

3. Configure environment variables
Create a `.env` file:

```
GOOGLE_SERVICE_ACCOUNT_EMAIL=your-service-account-email@example.com
GOOGLE_PRIVATE_KEY=your-private-key-here
```

4. Run in development mode

```bash
pnpm dev
```

5. Build production version

```bash
pnpm build
```

## Loading the Extension in Chrome

1. Open Chrome extensions management page (`chrome://extensions/`)
2. Enable "Developer mode"
3. Click "Load unpacked"
4. Select the project's `build/chrome-mv3-dev` directory

## Usage Instructions

1. Click the extension icon to open the sidebar
2. Complete Google account authorization
3. Configure target sheets and save rules
4. Use context menu or automatic matching to save content

## Contributing Guidelines

Pull Requests and Issues are welcome. Before submitting code, please ensure:

- Follow the project's code style
- Add necessary tests
- Update relevant documentation

## License

[MIT License](LICENSE)

## Feedback

For issues or suggestions, please [submit an Issue](https://github.com/aluoapp/save-to-sheets-extension/issues)
