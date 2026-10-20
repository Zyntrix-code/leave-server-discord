# Server Leave ⚡

A modern, fast, and secure Discord self-bot web dashboard designed to manage and bulk-leave Discord servers safely with rate-limit protection.

---

## 🌟 Features

- **🖤 Sleek Dark UI**: Modern pure-black aesthetic (`#000000`) with subtle accents, custom scrollbars, and smooth micro-animations.
- **📱 Responsive Server Grid**: Side-by-side server cards with instant search filtering by server name or server ID.
- **⚡ Bulk Selection**: One-click **Select All** / **Deselect All** with a real-time selection badge and floating leave button.
- **🛡️ Custom Modal Confirmations**: Zero browser `alert()` or `confirm()` popups. Built-in modern confirmation and warning modals.
- **👑 Server Owner Protection**: Detects servers where your account is the **Owner**. Instead of crashing, the tool skips them and continues processing the rest of your selected servers.
- **⏱️ Rate-Limit Protection**: Automatic 1-second delay between leave requests to safeguard your account against Discord API rate limits.
- **📊 Detailed Results Breakdown**: Clear post-action report showing successful leaves, remaining servers in your account, and exact failure reasons (e.g. server ownership).
- **🔒 Privacy & Code Obfuscation**: Source code is fully obfuscated for security and protection. Your account token stays strictly in local memory and is never shared, logged, or stored remotely.

---

## 🚀 Quick Start

### 1. Requirements
- [Node.js](https://nodejs.org/) (version 16.x or higher)

### 2. Installation
Open your terminal in the project folder and install dependencies:
```bash
npm install
```

### 3. Run the Application
Start the server:
```bash
node .
```
Open your browser and navigate to:
```
http://localhost:3000
```

---

## ⚙️ Configuration (Change Port)

You can easily change the port directly in [config.json](file:///h:/Shadow%20Porject/Bot%20discord/self-bots/L-Server/config.json):

```json
{
  "port": 3000
}
```
Change `3000` to any desired port (e.g., `8080`, `5000`), save the file, and restart the app.

---

## 📁 Project Structure

```
L-Server/
├── config.json       # Application configuration (port, etc.)
├── index.js          # Obfuscated Express server & Discord client logic
├── index.source.js   # Original clean source code (backup)
├── package.json      # Dependencies and metadata
├── views/
│   ├── login.ejs     # Token authentication view
│   ├── dashboard.ejs # Server grid, search, and selection view
│   └── result.ejs    # Detailed operation summary and statistics
└── README.md         # Project documentation
```

---

## ⚠️ Disclaimer

Using self-bots is against the [Discord Terms of Service](https://discord.com/terms). This tool is developed strictly for educational and personal utility purposes. Use at your own risk.
