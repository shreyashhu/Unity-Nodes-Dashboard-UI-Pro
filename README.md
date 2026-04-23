# Unity Nodes Dashboard Pro

**v1.1 | By @AlpraxIsHim**

A premium Tampermonkey userscript that enhances the Unity Nodes interface with advanced analytics, multi-account management, Google Sheets integration, and a fully customizable dashboard.

## Features

### Analytics & Charts
- **Interactive Graphs**: Visualize earnings with detailed bar charts
- **Time Ranges**: Switch between Last 7 Days, Last 30 Days, or Custom Date Range
- **Device Filtering**: Click any device/license to filter the graph and view only that specific device's earnings
- **Detailed Stats**: Track lifetime earnings, recent payouts, and 7-day averages

### Multi-Account Management
- Switch between multiple Unity Nodes accounts without logging out
- Persistent account storage via local storage
- Easy account management interface

### Google Sheets Integration
- **Auto-Sync**: Automatically send daily earnings and node stats to Google Sheets
- **One-Click Setup**: Paste your Apps Script Web App URL to configure
- **Manual Sync**: Trigger sync manually when needed

### Customizable UI
- **Dark/Light Mode**: Toggle between themes
- **Theme Customization**: Change accent colors, transparency, and blur intensity
- **Floating Window**: Fully draggable and resizable dashboard

### Utility Tools
- **Data Export**: Export data to CSV or JSON format
- **Manual Entry**: Manually input data if needed
- **Device Renaming**: Nickname your devices for easy identification

## Installation

1. **Install a Userscript Manager**:
   - Install [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Edge, Safari) or [Violentmonkey](https://violentmonkey.github.io/) (Firefox)

2. **Install the Script**:
   - Click the "Raw" button on this page
   - Click "Install" when prompted by your userscript manager

3. **Run**:
   - Go to [Unity Nodes Dashboard](https://manage.unitynodes.io/)
   - The dashboard overlay will load automatically

## Configuration

### Google Sheets Setup
1. Create a Google Sheet and link it to a Google Apps Script deployment
2. Deploy the script as a Web App (Access: Anyone)
3. Copy the Web App URL
4. Click the "Sheets Setup" button in the dashboard and paste the URL

### Theme Settings
- Click the Settings (⚙️) icon in the header
- Toggle Light/Dark mode
- Pick a custom accent color
- Adjust opacity/transparency slider

## Changelog

### v1.1
- Added Per-Device Graph Filtering (click device to see specific earnings)
- Added Rename Device functionality
- Enhanced UI with iOS-style Glassmorphism
- Fixed chart label overlapping issues
- Added Custom Date Range support

### v1.0
- Initial release with Dashboard Overlay, Multi-Account, and Sheets Sync

## Disclaimer
- **Use at Your Own Risk**: This script interacts with the Unity Nodes interface and API
- **Not Affiliated**: This project is not affiliated with Unity Nodes
- **API Security**: This script uses your local browser session token to fetch data. It does not store your password

## Support
For suggestions, issues, or feedback, DM me on Telegram: [@AlpraxIsHim](https://t.me/AlpraxIsHim)

---

**Made by [AlpraxIsHim](https://t.me/AlpraxIsHim)**
