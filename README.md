# Unity Nodes / UNetwork Dashboard Pro

**v2.3.1 | By @AlpraxIsHim** | [Telegram Support](https://t.me/AlpraxIsHim)

A lightweight, high-performance Tampermonkey userscript that transforms the **Unity Nodes** and **UNetwork** interfaces into a professional analytics dashboard. Featuring advanced distribution charts, multi-account management, automated syncing, and a fully customizable UI in just ~2100 lines of optimized code.

## 🚀 What's New in v2.3.1

-   **Optimized Core:** Streamlined codebase from ~2800 to ~2100 lines, removing redundant logic for faster load times and smoother performance.
-   **New Themes:** Added fresh accent colors and theme presets for enhanced visual customization.
-   **Enhanced Sheets Sync:** Improved reliability, error handling, and data formatting for Google Sheets integration.
-   **Bug Fixes:** Resolved minor UI glitches and improved overall stability across both platforms.

## Core Features

### Advanced Analytics
-   **Distribution Chart:** Scatter plot showing individual lease payouts with an average trend line (filterable by 1–7 days).
-   **Device Sparklines:** Mini 7-day bar charts on each device card for instant trend visualization.
-   **Multi-Type Charts:** Toggle between Bar, Line, and Area styles for main earnings graphs.
-   **Comparison View:** Side-by-side node analysis with selectable metrics (Recent, Daily Avg, 30D, Total).

### Automation & Control
-   **Configurable Refresh:** Set custom auto-refresh intervals (10s–10m) with a live countdown timer.
-   **Peak Tracker:** Automatically records the highest number of simultaneously active nodes.
-   **Compact Mode:** Minimize to a sleek balance strip view (`M` key or button).

### Multi-Platform & Accounts
-   **Dual Support:** Works seamlessly on both `manage.unitynodes.io` and `manage.unetwork.io`.
-   **Multi-Account Tabs:** Switch between accounts or view combined stats.
-   **Manual Entry:** Log earnings manually if API data is missing.

### Data & Sync
-   **Google Sheets Integration:** Auto-sync earnings via Webhook on every refresh.
-   **Export Options:** Download historical data as CSV or JSON.
-   **Device Nicknames:** Rename devices locally for easy identification.

### Customizable UI
-   **Theme Engine:** Dark/Light modes, 8+ accent colors, glass opacity, and blur control.
-   **Drag & Resize:** Fully movable overlay with persistent position saving.
-   **Keyboard Shortcuts:** `R` (Refresh), `F` (Fit), `M` (Minimize), `S` (Settings), `G` (Range), `Esc` (Clear Filter).

## Installation

1.  **Install a Userscript Manager:**
    -   [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Edge, Safari)
    -   [Violentmonkey](https://violentmonkey.github.io/) (Firefox)

2.  **Install the Script:**
    -   Click the **"Raw"** button on this repository.
    -   Click **"Install"** when prompted.

3.  **Run:**
    -   Navigate to [Unity Nodes](https://manage.unitynodes.io/) or [UNetwork](https://manage.unetwork.io/).
    -   The dashboard will load automatically.

## Configuration

### Google Sheets Setup
1.  Create a Google Sheet linked to a Google Apps Script deployment.
2.  Deploy as Web App (Access: **Anyone**).
3.  Copy the **Web App URL**.
4.  Click **Sheets** in the dashboard header and paste the URL.

## Changelog

### v2.3.1
-   **Optimization:** Reduced code size from ~2800 to ~2100 lines for better performance.
-   **New:** Added fresh accent colors and theme presets.
-   **Improvement:** Enhanced Google Sheets sync reliability and data formatting.
-   **Fix:** Resolved minor UI bugs and stability issues.

### v2.3
-   **New:** License Earning Distribution Chart (Scatter plot).
-   **New:** Device Sparklines for 7-day trends.
-   **New:** Compact/Minimize Mode & Live Countdown Timer.
-   **New:** Peak Active Nodes tracker.

### v2.1
-   Toast Notifications, Keyboard Shortcuts, Auto-resize charts.

### v2.0
-   Comparison Mode, Multi-Type Charts, Custom Refresh Intervals.

### v1.1
-   **New:** Added Per-Device Graph Filtering (click a device to isolate its earnings).
-   **New:** Device Renaming functionality via pencil icon.
-   **UI:** Enhanced visual design with iOS-style Glassmorphism effects.
-   **Fix:** Improved chart label readability and layout stability.

### v1.0
-   **Initial Release:** Introduced the floating dashboard overlay.
-   **Core Features:** Multi-account management, real-time earnings stats, and Google Sheets auto-sync.
-   **Analytics:** Basic bar chart visualization for daily earnings.
-   **UI:** Draggable and resizable window with dark/light theme support.

## Disclaimer
-   **Use at Your Own Risk:** Not affiliated with Unity Nodes or UNetwork.
-   **Security:** Uses local session tokens only. No passwords stored.

## Support
For feedback or bugs, DM [@AlpraxIsHim](https://t.me/AlpraxIsHim) on Telegram.

---

**Developed by [AlpraxIsHim](https://t.me/AlpraxIsHim)**
