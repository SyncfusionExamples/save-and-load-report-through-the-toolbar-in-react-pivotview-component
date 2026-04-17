# 📊 Save and Load Reports in React PivotView Component

[![React](https://img.shields.io/badge/React-18.3.1-61DAFB.svg?logo=react)](https://reactjs.org) 
[![Syncfusion React](https://img.shields.io/badge/Syncfusion%20-React-0078D4.svg)](https://www.syncfusion.com/react-components) 
[![License](https://img.shields.io/badge/license-SEE%20LICENSE-blue.svg)](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf)
[![Node.js](https://img.shields.io/badge/Node.js-14+-339933.svg?logo=node.js)](https://nodejs.org/)

> **Production-ready React implementation for saving and loading pivot table reports** — Seamlessly persist pivot table configurations using Syncfusion EJ2 PivotView toolbar integration with modern React patterns and best practices.

## 🎯 Overview

This repository delivers a complete, enterprise-ready solution for implementing **save and load functionality** in the Syncfusion React PivotView component. Perfect for building business intelligence dashboards, financial reporting tools, and analytics applications. The toolbar-integrated report management system allows users to persist complex pivot configurations and restore them instantly with zero data loss.

**Repository Description:** Complete React implementation demonstrating seamless integration of save and load functionality for reports in Syncfusion React PivotView, with toolbar integration and persistent state management for efficient data analysis workflows.

## ✨ Key Features

- ✅ **Save Reports**: Export pivot configurations to JSON format via toolbar button
- ✅ **Load Reports**: Restore saved reports with single-click file upload
- ✅ **Toolbar Integration**: Intuitive UI controls within EJ2 PivotView toolbar
- ✅ **React 18 Support**: Latest React patterns with functional components
- ✅ **Syncfusion EJ2 PivotView**: Enterprise-grade pivot table with advanced analytics
- ✅ **File-Based Persistence**: Direct JSON download and upload capabilities
- ✅ **Zero Dependencies**: No external storage services required

## 🛠 Prerequisites & Requirements

- **Node.js**: v14.0 or later
- **npm**: v6.0 or later (or yarn)
- **React**: 18.3.1+
- **Syncfusion License**: Community or commercial license
- **Browser Support**: Chrome 90+, Firefox 88+, Safari 14+, Edge 90+

## 📦 Installation & Setup

1. **Clone Repository**
   ```bash
   git clone https://github.com/SyncfusionExamples/save-and-load-report-through-the-toolbar-in-react-pivotview-component
   cd save-and-load-report-through-the-toolbar-in-react-pivotview-component
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```
   This installs React 18.3.1, Syncfusion EJ2 PivotView 26.1.39, and testing utilities.

3. **Verify Installation**: Check that `node_modules` contains `@syncfusion/ej2-react-pivotview`

## 🚀 Quick Start

1. **Start Development Server**
   ```bash
   npm start
   ```
   Application opens at `http://localhost:3000` with hot-reload enabled.

2. **Interact with PivotView**
   - Rearrange rows, columns, and values
   - Apply filters and formatting
   - Drag fields to reshape data analysis view

3. **Save Report**
   - Click the **Save** button in toolbar
   - Browser downloads `pivot.JSON` containing your configuration

4. **Load Report**
   - Click the **Open** button in toolbar
   - Select a previously saved `pivot.JSON` file
   - PivotView instantly restores the saved configuration

## 🗂 Project Structure

```
├── src/
│   ├── App.js              # Main PivotView component with save/load logic
│   ├── datasource.js       # Sample pivot data source
│   ├── index.js            # React application entry point
│   └── index.css           # Styling
├── public/
│   ├── index.html          # HTML template
│   └── manifest.json       # PWA manifest
├── package.json            # Dependencies and scripts
└── README.md               # This file
```

## 🧩 Core Implementation

The save/load functionality leverages:
- **`getPersistData()`**: Extracts pivot configuration as JSON
- **`dataSourceSettings`**: Applies saved configuration to restore report
- **FileReader API**: Handles file uploads for loading reports
- **Base64 Encoding**: Enables JSON-to-download conversion

## 🔧 Available Scripts

```bash
npm start       # Run development server (port 3000)
npm build       # Build optimized production bundle
npm test        # Execute test suite
npm eject       # Eject from react-scripts (irreversible)
```

## 📚 Resources & Documentation

- [Syncfusion React PivotView Docs](https://www.syncfusion.com/react-components/react-pivot-table)
- [Syncfusion PivotView Toolbar Guide](https://ej2.syncfusion.com/react/documentation/pivotview/tool-bar)
- [React Official Documentation](https://react.dev)
- [MDN FileReader API](https://developer.mozilla.org/en-US/docs/Web/API/FileReader)

## 🤝 Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the **Syncfusion Community License**. See [Syncfusion License](https://www.syncfusion.com/content/downloads/syncfusion_license.pdf) for details.

## 🆘 Support

For issues, questions, or suggestions:
- 📧 Open an [Issue](https://github.com/SyncfusionExamples/save-and-load-report-through-the-toolbar-in-react-pivotview-component/issues)
- 💬 Visit [Syncfusion React Support](https://www.syncfusion.com/forums/react-js2)
- 📖 Check [Syncfusion Documentation](https://ej2.syncfusion.com/react/documentation/pivotview/getting-started)
