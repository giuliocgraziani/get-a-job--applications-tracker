# Get-a-Job | Application Tracker

A powerful, feature-rich web application for tracking internship applications. Built with React, runs entirely in your browser - no backend required.

[![Live Demo](https://img.shields.io/badge/Live-Demo-blue?style=for-the-badge&logo=github)](https://giuliocgraziani.github.io/get-a-job--applications-tracker/)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

## ✨ Features

### Core Tracking
- 📝 **Custom Categories** - International Org, Central Bank, Research Centre, and more (+ add your own)
- 📅 **Multiple Deadlines** - Track application deadline, interviews, tests, outcome dates
- ⏰ **Smart Alerts** - Company names turn red 2 days before deadline
- 💰 **Stipend Tracking** - Mark positions as paid/unpaid with amount
- 📍 **Flexible Location** - Remote, hybrid, city names, or custom
- 🎓 **Education Requirements** - Track degree requirements
- 📎 **Materials Checklist** - CV, cover letter, other documents
- 🔗 **External Links** - Quick access to position websites
- 📝 **Notes** - Store interview details, contacts, insights

### Visualization & Views
- 📊 **List View** - Detailed cards with all information
- 📋 **Compact Table View** - Streamlined table for quick scanning
- 📅 **Calendar View** - Monthly overview with color-coded events
- 📈 **Status Breakdown** - Pie chart showing application pipeline

### Data Management
- 🔍 **Advanced Filtering** - Filter by status, cycle, category, stipend
- 🔎 **Search** - Find applications instantly
- 📤 **Export to CSV** - Download spreadsheet for analysis
- 💾 **Backup & Restore** - Complete data export/import (JSON)
- 🎨 **Responsive Design** - Works on desktop, tablet, mobile

## 🚀 Quick Start

### Option 1: Use Online (Recommended)
Simply visit the [Live Demo](https://yourusername.github.io/tracktern/)

### Option 2: Download and Run Locally
1. Download `index.html`
2. Open it in any modern browser (Chrome, Firefox, Safari, Edge)
3. Start tracking your applications!

No installation, no setup, no dependencies required.

## 📊 Status Workflow

```
Upcoming → Applied → Invited for Interview → Step 2 → Final Step → Offered → Accepted
                                                                    ↓
                                                                Rejected / Withdrawn
```

## 🎯 Usage Guide

### Adding Applications
1. Click **"+ Add Position"** button
2. Fill in company name and position (required)
3. Add optional details: deadline, location, stipend, etc.
4. Add additional deadlines (interviews, tests)
5. Save and track!

### View Modes
- **List View**: Detailed cards, perfect for reviewing individual applications
- **Compact View**: Table format, great for comparing many positions at once
- **Calendar View**: See all deadlines and events in monthly calendar

### Filtering & Search
- Use filters to focus on specific types of positions
- Search by company name, position title, or category
- Combine multiple filters for precise results

### Export & Backup
- **CSV Export**: Download spreadsheet for Excel/Google Sheets
- **Backup**: Export complete data as JSON file (includes custom categories)
- **Import**: Restore from backup file to transfer between devices

## 💡 Pro Tips

1. **Add positions early** - Track opportunities before you apply
2. **Use deadline alerts** - Never miss a deadline with red color coding
3. **Multiple deadlines** - Track interviews, tests, outcome dates separately
4. **Compact view** - Efficiently scan 50+ applications at once
5. **Regular backups** - Export your data weekly to avoid loss
6. **Position links** - Quick access to application portals
7. **Custom categories** - Create categories that match your job search

## 🛠️ Technical Details

- **Framework**: React 18 (via CDN)
- **Styling**: Tailwind CSS + Custom CSS
- **Storage**: LocalStorage (browser-based)
- **No Backend**: Runs entirely client-side
- **No Installation**: Open HTML file and start using

## 📱 Browser Compatibility

- ✅ Chrome 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Edge 90+

## 🎨 Features Showcase

### Compact View
Perfect for scanning many applications quickly:
- See Company, Position, Deadline, Status, Stipend, Location in one table
- Click 👁️ to view full details in a modal
- Click 🔗 to open position website
- Click ✏️ to edit

### Calendar View
Visual timeline of your application journey:
- **Purple** = Application deadlines
- **Blue** = Applied dates
- **Amber** = Additional events (interviews, tests)

### Smart Filters
Narrow down your applications:
- Filter by Status (Upcoming, Applied, Interview stages, etc.)
- Filter by Cycle (Spring, Summer, Fall, Winter)
- Filter by Category (Central Bank, Tech, Consulting, etc.)
- Filter by Stipend (Yes/No)

## 🔐 Privacy

All data is stored locally in your browser. Nothing is sent to any server. Your application data never leaves your device. MAKE SURE TO BACKUP YOUR PROGRESS or you risk losing it all if your browser's metadata gets deleted.

## 📄 License

MIT License - Free to use, modify, and distribute.
