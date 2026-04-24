# Unity Nodes Dashboard Pro

**v2.1 | By @AlpraxIsHim** | [Telegram Support](https://t.me/AlpraxIsHim)

A premium Tampermonkey userscript that transforms the Unity Nodes interface into a powerful analytics dashboard. Featuring device comparison, multi-type charts, historical data export, and a polished, responsive UI.

##  What's New in v2.1

-   **Toast Notifications:** Replaced intrusive browser alerts with sleek, non-blocking toast notifications for actions like saving accounts or syncing sheets.
-   **Device Sparklines:** Added mini trend graphs to the device list, allowing you to visualize recent earnings performance for each node at a glance.
-   **Keyboard Shortcuts:** Navigate faster with hotkeys for Refresh (`R`), Settings (`S`), and View Switching (`Tab`).
-   **Compact Mode:** A new minimize feature reduces the dashboard footprint while keeping essential balance and status info visible.
-   **Auto-Resize Charts:** Integrated `ResizeObserver` to ensure graphs automatically redraw and adjust perfectly when you resize the dashboard window.
-   **Systematic Improvements:** Optimized layout stability, fixed minor rendering glitches, and refined code structure for better performance.

## Core Features

### Advanced Analytics
-   **Interactive Graphs:** Visualize earnings with customizable chart types (Bar, Line, Area).
-   **Time Ranges:** Analyze data over Last 7 Days, Last 30 Days, or a Custom Date Range.
-   **Device Filtering:** Click any device in the list to isolate its earnings on the main graph.
-   **Comparison Mode:** Compare multiple licenses/devices side-by-side across different metrics (Recent, Daily Avg, 30D Total, Lifetime).

### Multi-Account Management
-   Seamlessly switch between multiple Unity Nodes accounts.
-   Persistent local storage for account credentials.
-   Easy-to-use account manager with edit/remove capabilities.

### Google Sheets Integration
-   **Auto-Sync:** Automatically push daily earnings and node stats to Google Sheets.
-   **One-Click Setup:** Simple configuration via Web App URL.

### Customizable UI
-   **Dark/Light Mode:** Toggle themes to suit your preference.
-   **Theme Engine:** Customize accent colors, transparency, and glassmorphism effects.
-   **Floating Window:** Fully draggable and resizable overlay with snap-to-center functionality.

## Installation

1.  **Install a Userscript Manager:**
    -   [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Edge, Safari)
    -   [Violentmonkey](https://violentmonkey.github.io/) (Firefox)

2.  **Install the Script:**
    -   Click the **"Raw"** button on this repository.
    -   Click **"Install"** when prompted by your extension.

3.  **Run:**
    -   Navigate to [Unity Nodes Dashboard](https://manage.unitynodes.io/).
    -   The dashboard overlay will load automatically.

## Configuration

### Google Sheets Setup
1.  Create a Google Sheet and link it to a Google Apps Script deployment.
2.  Deploy the script as a Web App (Access: **Anyone**).
3.  Copy the **Web App URL**.
4.  Click **Sheets Setup** in the dashboard and paste the URL.

### Keyboard Shortcuts
-   `R`: Refresh Data
-   `S`: Open Settings
-   `Tab`: Switch between Dashboard and Comparison views
-   `Esc`: Close Modals

### Dashboard Settings
-   **Auto-Refresh Interval:** Go to Settings > Refresh to set custom refresh times (10s–600s).
-   **Chart Type:** Use the chart controls to switch between Bar, Line, and Area views.
-   **Themes:** Customize colors and opacity in the Theme tab.

## Changelog

### v2.1
-   **New:** Added **Toast Notifications** for a cleaner user experience.
-   **New:** Added **Device Sparklines** to visualize per-node trends.
-   **New:** Implemented **Keyboard Shortcuts** for navigation.
-   **New:** Added **Compact/Minimize Mode** for reduced footprint.
-   **Fix:** Integrated **ResizeObserver** for dynamic chart resizing.
-   **Improvement:** Systematic code optimization and layout stability fixes.

### v2.0
-   **New:** Added **Comparison Mode** for side-by-side device/license analysis.
-   **New:** Added **Multi-Type Charts** (Bar, Line, Area) for better trend visualization.
-   **New:** Custom **Auto-Refresh Interval** settings.
-   **Fixed:** CSV Export now correctly includes all historical and manual records.
-   **Fixed:** Active licenses no longer incorrectly show as inactive.
-   **UI:** Improved fonts, text rendering, and overall design polish.

### v1.1
-   Added Per-Device Graph Filtering.
-   Added Rename Device functionality.
-   Enhanced UI with iOS-style Glassmorphism.

### v1.0
-   Initial release with Dashboard Overlay, Multi-Account, and Sheets Sync.

## Disclaimer
-   **Use at Your Own Risk:** This script interacts with the Unity Nodes API. The author is not responsible for account issues.
-   **Not Affiliated:** This project is **not** affiliated with Unity Nodes.
-   **Security:** This script uses your local browser session token. It does not store passwords or send sensitive auth data to third parties.

## Support & Suggestions
For feature requests, bug reports, or feedback, please DM me on Telegram:  
👉 [@AlpraxIsHim](https://t.me/AlpraxIsHim)

---

**Developed by [AlpraxIsHim](https://t.me/AlpraxIsHim)**
