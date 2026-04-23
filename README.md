#  Unity Nodes Dashboard Pro

**v1.1 | By @AlpraxIsHim**

A powerful, feature-rich **Tampermonkey/Violentmonkey userscript** that enhances the Unity Nodes interface with a premium, floating dashboard. Unlock advanced analytics, multi-account management, automated Google Sheets syncing, and a fully customizable UI.

![Dashboard Preview](https://via.placeholder.com/800x400?text=Unity+Nodes+Dashboard+Pro+Preview)

##  Key Features

### 📊 Advanced Analytics & Charts
- **Interactive Graphs**: Visualize earnings with bar charts.
- **Time Ranges**: Switch between **Last 7 Days**, **Last 30 Days**, or a **Custom Date Range**.
- **Device Filtering**:  **Click any device/license** in the breakdown list to filter the graph and view **only that specific device's earnings**. Click again to reset.
- **Detailed Stats**: Lifetime earnings, recent payouts, and 7-day averages.

### 👥 Multi-Account Management
- Seamlessly switch between multiple Unity Nodes accounts without logging out.
- Persistent account storage via local storage.
- Easy "Add Account" and "Manage Accounts" interfaces.

### ☁️ Google Sheets Integration
- **Auto-Sync**: Automatically send your daily earnings and node stats to a Google Sheet.
- **One-Click Setup**: Paste your Apps Script Web App URL to configure instantly.
- **Manual Sync**: Trigger a sync manually if needed.

### 🎨 Customizable UI (iOS Glass Style)
- **Dark / Light Mode**: Toggle between themes based on your preference.
- **Theme Customization**: Change accent colors, background transparency, and glassmorphism blur intensity.
- **Floating Window**: Fully draggable and resizable dashboard overlay.

### 🛠️ Utility Tools
- **Data Export**: Export your node data and earnings to **CSV** or **JSON** format.
- **Manual Entry**: Manually input data if API fetch fails.
- **Device Renaming**: Click the ✏️ icon to nickname your devices for easy identification.

---

## 📥 Installation

1.  **Install a Userscript Manager**:
    - Install [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Edge, Safari) or [Violentmonkey](https://violentmonkey.github.io/) (Firefox).
2.  **Install the Script**:
    - Navigate to your repository or the raw script link.
    - Click **"Raw"**.
    - Click **"Install"** when prompted by your userscript manager.
3.  **Run**:
    - Go to the [Unity Nodes Dashboard](https://manage.unitynodes.io/).
    - The dashboard overlay will load automatically.

---

## ⚙️ Configuration

### 📊 Google Sheets Setup
1.  Create a Google Sheet and link it to a Google Apps Script deployment.
2.  Deploy the script as a Web App (Access: **Anyone**).
3.  Copy the **Web App URL**.
4.  Click the **Sheets Setup** button in the dashboard overlay and paste the URL.

### 🎨 Theme Settings
- Click the **⚙️ Settings** icon in the header.
- Toggle Light/Dark mode.
- Pick a custom accent color.
- Adjust opacity/transparency slider.

---

## ⚠️ Disclaimer
- **Use at Your Own Risk**: This script interacts with the Unity Nodes interface and API. While safe, the author is not responsible for any account issues.
- **Not Affiliated**: This project is **not** affiliated with Unity Nodes.
- **API Security**: This script uses your local browser session token to fetch data. It does not store your password.

---

## 📝 Changelog

### v1.1
- 🆕 Added **Per-Device Graph Filtering**: Click a device to see its specific earnings.
- 🆕 Added **Rename Device** functionality (✏️ icon).
- 🎨 Enhanced UI with iOS-style Glassmorphism.
- 🐛 Fixed chart label overlapping issues on large datasets.
- 📊 Added Custom Date Range support for graphs.

### v1.0
- Initial release with Dashboard Overlay, Multi-Account, and Sheets Sync.

---

## 📜 License
This project is for educational and personal use only.

---

**Made with ❤️ by [AlpraxIsHim](https://t.me/AlpraxIsHim)**
