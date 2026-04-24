# Unity Nodes Dashboard Pro v2.0

**By @AlpraxIsHim** | [Telegram Support](https://t.me/AlpraxIsHim)

A premium Tampermonkey userscript that transforms the Unity Nodes interface into a powerful analytics dashboard. Now featuring **Device Comparison**, **Multi-Type Charts**, and **Historical Data Export**.

![Dashboard Preview](https://via.placeholder.com/800x400?text=Unity+Nodes+Dashboard+Pro+v2.0)

## 🚀 What's New in v2.0

-   **⚖️ Device Comparison Mode:** Compare multiple licenses/devices side-by-side. View metrics for Daily Average, Most Recent Earnings, Past 30 Days, and Total Lifetime earnings simultaneously.
-   **📈 Multi-Type Charts:** Switch between **Bar**, **Line**, and **Area** graphs to visualize your earnings trends over 7 days, 30 days, or custom timeframes.
-   **💾 Historical CSV Export:** Fixed export logic to ensure all past records and manual entries are correctly included in your CSV downloads.
-   **⏱️ Custom Auto-Refresh:** Set your own interval (10s–600s) for dashboard auto-refreshes to keep data fresh without manual reloading.
-   **✅ Active Status Fix:** Resolved an issue where active licenses were incorrectly marked as inactive.
-   **✨ UI Polish:** Improved typography, font rendering, and overall design consistency with a new Frosted Glass aesthetic.

## Core Features

### Advanced Analytics
-   **Interactive Graphs:** Visualize earnings with customizable chart types (Bar, Line, Area).
-   **Time Ranges:** Analyze data over Last 7 Days, Last 30 Days, or a Custom Date Range.
-   **Device Filtering:** Click any device in the list to isolate its earnings on the main graph.
-   **Detailed Stats:** Track lifetime earnings, recent payouts, and averages.

### Multi-Account Management
-   Seamlessly switch between multiple Unity Nodes accounts.
-   Persistent local storage for account credentials.
-   Easy-to-use account manager.

### Google Sheets Integration
-   **Auto-Sync:** Automatically push daily earnings and node stats to Google Sheets.
-   **One-Click Setup:** Simple configuration via Web App URL.

### Customizable UI
-   **Dark/Light Mode:** Toggle themes to suit your preference.
-   **Theme Engine:** Customize accent colors, transparency, and glassmorphism effects.
-   **Floating Window:** Fully draggable and resizable overlay.

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

### Dashboard Settings
-   **Auto-Refresh Interval:** Go to Settings (⚙️) > Refresh to set custom refresh times.
-   **Chart Type:** Use the chart controls to switch between Bar, Line, and Area views.
-   **Themes:** Customize colors and opacity in the Theme tab.

## Changelog

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
