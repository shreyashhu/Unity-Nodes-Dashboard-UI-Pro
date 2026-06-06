# Unity Nodes Dashboard Pro

**v2.3 | By @AlpraxIsHim** | [Telegram Support](https://t.me/AlpraxIsHim)

A comprehensive Tampermonkey userscript that transforms the Unity Nodes interface into a powerful analytics and management dashboard. Featuring advanced distribution charts, multi-account support, automated syncing, and a fully customizable UI.

## 🚀 What's New in v2.3

-   **License Earning Distribution Chart:** A new scatter plot visualization showing individual lease payouts over time with an average trend line. Filterable by 1, 3, 5, or 7 days to spot trends instantly.
-   **Device Sparklines:** Mini 7-day bar charts added to each device card, providing a quick visual history of earning performance per node.
-   **Enhanced Comparison View:** A dedicated side-by-side node comparison tool with selectable metrics (Recent, Daily Avg, 30D Total, Lifetime) for deeper analysis.
-   **Configurable Automation:** Set custom auto-refresh intervals (from 10s to 10m) with a live countdown timer displayed in the footer.
-   **Peak Active Nodes Tracker:** Automatically records and displays the highest number of simultaneously active nodes detected during your session.
-   **Compact Mode:** Minimize the dashboard to a sleek balance strip view to save screen space, toggleable via the minimize button or `M` key.
-   **Live Theme Preview:** See accent color changes in real-time within the settings modal before applying them.

## Core Features

### Advanced Analytics
-   **Multi-Type Charts:** Toggle between Bar, Line, and Area styles for the main earnings graph.
-   **Time Ranges:** Analyze data over Last 7 Days, Last 30 Days, or a Custom Date Range.
-   **Device Filtering:** Click any device to isolate its earnings on the main graph; click the filter badge to clear.
-   **Detailed Stats:** Track lifetime earnings, recent payouts, daily averages, and peak activity.

### Multi-Account Management
-   **Account Tabs:** Seamlessly switch between multiple Unity Nodes accounts or view "All Accounts" combined.
-   **Manual Entry:** Log earnings manually with date, amount, node count, and notes if API data is missing.
-   **Persistent Storage:** Account credentials and device nicknames are saved locally.

### Data & Sync
-   **Google Sheets Integration:** Auto-sync daily earnings and node stats to Google Sheets via Webhook on every refresh.
-   **Export Options:** Download all historical data, device stats, and account history as CSV or JSON files.
-   **Device Nicknames:** Rename devices using the pencil icon for easier identification.

### Customizable UI
-   **Theme Engine:** Choose between Dark/Light modes, 8 accent color presets, and adjust glass opacity/blur intensity.
-   **Drag & Resize:** Fully movable and resizable overlay with persistent position saving.
-   **Keyboard Shortcuts:**
    -   `R`: Refresh Data
    -   `F`: Center & Fit Window
    -   `M`: Toggle Compact Mode
    -   `S`: Open Settings
    -   `G`: Open Graph Range Selector
    -   `Esc`: Clear Device Filter / Close Modals

## Installation

1.  **Install a Userscript Manager:**
    -   [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Edge, Safari)
    -   [Violentmonkey](https://violentmonkey.github.io/) (Firefox)

2.  **Install the Script:**
    -   Click the **"Raw"** button on this repository.
    -   Click **"Install"** when prompted by your extension.

3.  **Run:**
    -   Navigate to [Unity Nodes Dashboard](https://manage.unitynodes.io/) or [UNetwork](https://manage.unetwork.io/).
    -   The dashboard overlay will load automatically.

## Configuration

### Google Sheets Setup
1.  Create a Google Sheet and link it to a Google Apps Script deployment.
2.  Deploy the script as a Web App (Access: **Anyone**).
3.  Copy the **Web App URL**.
4.  Click **Sheets** in the dashboard header and paste the URL.

### Dashboard Settings
-   **Auto-Refresh:** Go to Settings > Refresh to set custom intervals.
-   **Themes:** Customize colors, opacity, and blur in the Theme tab.
-   **Chart Types:** Use the toolbar above the main chart to switch between Bar, Line, and Area views.

## Changelog

### v2.3
-   **New:** Added **License Earning Distribution Chart** (Scatter plot with avg line).
-   **New:** Added **Device Sparklines** for 7-day trend visualization.
-   **New:** Enhanced **Comparison View** with metric selection.
-   **New:** **Peak Active Nodes** tracker.
-   **New:** **Compact/Minimize Mode** for reduced footprint.
-   **New:** **Live Countdown Timer** for auto-refresh.
-   **Improvement:** Real-time **Theme Preview** in settings.
-   **Fix:** Improved error handling and resize observer integration.

### v2.1
-   **New:** Toast Notifications replacing alerts.
-   **New:** Keyboard Shortcuts.
-   **New:** Auto-resize charts on window resize.

### v2.0
-   **New:** Comparison Mode for side-by-side analysis.
-   **New:** Multi-Type Charts (Bar, Line, Area).
-   **New:** Custom Auto-Refresh Intervals.
-   **Fixed:** CSV Export logic and active license status.

### v1.1
-   Added Per-Device Graph Filtering.
-   Added Rename Device functionality.
-   Enhanced UI with Glassmorphism.

### v1.0
-   Initial release with Dashboard Overlay, Multi-Account, and Sheets Sync.

## Disclaimer
-   **Use at Your Own Risk:** This script interacts with the Unity Nodes/UNetwork API. The author is not responsible for account issues.
-   **Not Affiliated:** This project is **not** affiliated with Unity Nodes or UNetwork.
-   **Security:** This script uses your local browser session token. It does not store passwords or send sensitive auth data to third parties (except to your configured Google Sheet if enabled).

## Support & Suggestions
For feature requests, bug reports, or feedback, please DM me on Telegram:  
👉 [@AlpraxIsHim](https://t.me/AlpraxIsHim)

---

**Developed by [AlpraxIsHim](https://t.me/AlpraxIsHim)**
