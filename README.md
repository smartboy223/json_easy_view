# 📊 JSON Viewer Pro

```

     ██╗ ███████╗  ██████╗  ███╗   ██╗
     ██║ ██╔════╝ ██╔═══██╗ ████╗  ██║
     ██║ ███████╗ ██║   ██║ ██╔██╗ ██║
██   ██║ ╚════██║ ██║   ██║ ██║╚██╗██║
╚█████╔╝ ███████║ ╚██████╔╝ ██║ ╚████║
 ╚════╝  ╚══════╝  ╚═════╝  ╚═╝  ╚═══╝



██╗   ██╗ ██╗ ███████╗ ██╗    ██╗ ███████╗ ██████╗
██║   ██║ ██║ ██╔════╝ ██║    ██║ ██╔════╝ ██╔══██╗
██║   ██║ ██║ █████╗   ██║ █╗ ██║ █████╗   ██████╔╝
╚██╗ ██╔╝ ██║ ██╔══╝   ██║███╗██║ ██╔══╝   ██╔══██╗
 ╚████╔╝  ██║ ███████╗ ╚███╔███╔╝ ███████╗ ██║  ██║
  ╚═══╝   ╚═╝ ╚══════╝  ╚══╝╚══╝  ╚══════╝ ╚═╝  ╚═╝


```

A professional, feature-rich JSON and CSV data viewer that runs entirely in your browser. No server required, no data leaves your machine. 🚀

![JSON Viewer Pro Screenshot](screenshot.png)

---

## ✨ Features

### 📥 Core Functionality
- **🔄 Dual Format Support**: Load and view both JSON and CSV files
- **📤 Drag & Drop**: Simply drag files onto the drop zone or click to browse
- **⚡ Large File Handling**: Efficiently handles files with thousands of records
- **🔒 Client-Side Only**: Your data never leaves your browser

### 👁️ Data Viewing
- **📊 Interactive Table**: Sortable, clickable rows with hover effects
- **📄 Pagination**: Navigate through large datasets with customizable page sizes
- **🎨 Column Selection**: Automatically detects and displays relevant columns
- **🔍 Row Details**: Click any row to view the complete JSON in a syntax-highlighted modal

### 🔎 Search & Filter
- **🌍 Global Search**: Search across all fields simultaneously
- **🎯 Field-Specific Search**: Target specific columns for precise filtering
- **⚡ Real-time Filtering**: Results update as you type (with debouncing)
- **🔤 Case-Insensitive**: Searches are case-insensitive for better matching

### 💾 Data Export
- **📤 JSON Export**: Export filtered results to JSON format
- **⌨️ Keyboard Shortcut**: Press `Ctrl+E` (or `Cmd+E` on Mac) to export
- **📅 Timestamped Files**: Exported files include the current date

### 🎨 Themes
- **🌙 Dark Mode**: Easy on the eyes, perfect for late-night data analysis
- **☀️ Light Mode**: Clean, professional look for presentations
- **💾 Persistent Preference**: Your theme choice is saved in localStorage
- **🖥️ System Integration**: Respects your system's theme preference (optional)

### ⌨️ User Experience
- **⌨️ Keyboard Shortcuts**:
  - `Ctrl+F` / `Cmd+F`: Focus search box 🔍
  - `Ctrl+E` / `Cmd+E`: Export data 💾
  - `Escape`: Close modals ❌
- **📱 Responsive Design**: Works on desktops, tablets, and mobile devices
- **⏳ Loading States**: Visual feedback when processing large files
- **⚠️ Error Handling**: Clear error messages if something goes wrong

---

## 🚀 Usage

### 🏃 Quick Start
1. Open `index.html` in any modern web browser 🌐
2. Drag a JSON or CSV file onto the drop zone, or click to browse 📤
3. Explore your data using the table, search, and filter tools 🔍

### 🧪 Sample Data
A `sample-data.json` file is included for testing. It contains:
- 👥 5 user records with nested objects and arrays
- 📊 Various data types: strings, numbers, booleans, dates
- 🏗️ Complex structures: objects within objects, arrays of objects

### 📋 Supported File Formats

#### 📄 JSON
- Standard JSON files (`.json`)
- Arrays of objects
- Objects with nested properties
- Large files (tested up to 50MB)

#### 📊 CSV
- Standard CSV files (`.csv`)
- Comma-separated values
- Double-quoted fields with escaped quotes
- Header row required

---

## 🌐 Browser Compatibility

| Browser | Version |
|---------|---------|
| Chrome | 80+ ✅ |
| Firefox | 75+ ✅ |
| Safari | 13.1+ ✅ |
| Edge | 80+ ✅ |

Requires ES6+ support (arrow functions, const/let, async/await).

---

## 🔒 Privacy & Security

- **🔐 100% Client-Side**: No data is sent to any server
- **🚫 No Tracking**: No analytics, cookies, or external requests
- **📖 Open Source**: You can inspect all the code
- **🛡️ File Access**: Files are read via the File API, never uploaded

---

## 🛠️ Development

### 📁 Project Structure
```
📦 json_easy_view/
├── 📄 index.html          # Main application (single-file)
├── 📄 sample-data.json    # Sample data for testing
├── 📄 README.md           # This file
└── 🖼️ screenshot.png      # App screenshot (optional)
```

### 💻 Local Development
Since this is a static HTML file, you can simply open `index.html` directly in your browser. For a more development-friendly experience:

```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve

# PHP
php -S localhost:8080
```

Then open `http://localhost:8080` in your browser.

### 📝 Code Style
- ES6+ JavaScript (no transpilation needed for modern browsers)
- CSS custom properties for theming
- Semantic HTML5 elements
- Accessible ARIA labels where needed

### 🔮 Future Enhancements

Potential features for future versions:

- [ ] 📊 Sort columns by clicking headers
- [ ] 💾 Save/load filter presets
- [ ] 🌐 Import from URL (CORS-permitting)
- [ ] 📈 Data visualization (charts/graphs)
- [ ] 🗄️ SQL-like query interface
- [ ] 📑 Multi-file comparison
- [ ] 👥 Collaborative editing (WebRTC)

---

## 📜 License

MIT License - feel free to use, modify, and distribute as you wish. 🎉

---

## 🙏 Credits

Built with ❤️ using vanilla JavaScript, modern CSS, and web standards.

---

**💡 Tip**: Try loading the `sample-data.json` file to explore all the features! 🚀
