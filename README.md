# Enhanced Order Form v2.1

## 🚀 Live Demo
**[View Live Form →](https://silver-fox-marketing.github.io/enhanced-order-form-v2.0/)**

## 📋 Overview
A professional order processing tool designed for Silver Fox Marketing's vehicle merchandising workflow. This form streamlines the creation of variable data orders for VersaWorks RIP software with advanced features like keyboard shortcuts, drag-and-drop reordering, Google Drive integration, and a complete field locking system for optimal workflow efficiency.

## ✨ Key Features

### 📝 Product Types
- **Windshields** - Flyout, Triangle, Oval, and Upper-Triangle configurations
  - **Flyout Type**: Special 4-field layout (Flyout 1, Mainline 1, Mainline 2, Misc)
  - **Standard Types**: 3-field layout (Mainline 1, Mainline 2, Misc)
- **Body Sides** - Standard and Oval body side graphics
- **Complements** - Inverted-Triangle and Oval-Comp options
- **Custom Products** - Flexible fields for special orders
- **Dealership Merchandising** - Location-specific installations

### 🔒 Field Locking System (NEW in v2.1)
- **Sequential Revelation**: Type → Size → Material → Text Fields
- **Visual Locking Indicators**: Green badges with unlock options
- **VersaWorks Compatibility**: Static selections prevent accidental changes
- **Smart Multiple Items**: Button only appears when all required fields are locked

### ⌨️ Keyboard Shortcuts (Multiple Items Modal)
- `Enter` - Move to next row (auto-creates new row at bottom)
- `Shift + Enter` - Move to previous row
- `Tab` - Navigate to next cell
- `Shift + Tab` - Navigate to previous cell
- `Ctrl + Enter` - Apply changes and close modal
- `Ctrl + D` - Duplicate current row
- `Ctrl + Delete` - Delete current row
- `Escape` - Cancel and close modal

### 🎯 Smart Features
- **Drag & Drop Row Reordering** - Reorganize entries with visual drag handles
- **Triple Locking System** - Type, Size, and Material all lock for VersaWorks compatibility
- **Character Limit Recommendations** - Visual feedback for optimal text length
- **Auto-Save with Browser Cache** - 24-hour data persistence
- **Single & Bulk Entry Modes** - Flexible data input options
- **Streamlined Multiple Items** - Material dropdown removed from modals (uses locked values)

### 📤 Export Capabilities
- **CSV Export** - VersaWorks-compatible format with quantity expansion
- **Google Drive Integration** - Automatic upload to configured folder
- **Order Summary** - Real-time preview of order details

## 🛠️ Technical Details

### Browser Compatibility
- Chrome (recommended)
- Firefox
- Safari
- Edge

### Material Options
- Winter
- Summer
- Perf

### Size Options
- Small
- Medium
- Large
- X-Large (Body Sides only)

## 📊 CSV Export Format
The form generates CSV files optimized for VersaWorks variable data printing:
- **Quantities Expanded**: 5 qty = 5 individual rows with qty 1
- **Static Values**: Size and Material locked across all entries
- **Dynamic Headers**: Automatically adjust for Flyout vs Standard windshields
- **Flyout Windshields**: `QTY, Windshield Type, Flyout 1, Mainline 1, Mainline 2, Misc, Material, Size`
- **Standard Windshields**: `QTY, Windshield Type, Mainline 1, Mainline 2, Misc, Material, Size`
- **Body Sides/Complements**: `QTY, Type, Mainline 1, Mainline 2, Misc, Material, Size`

## 🔗 Google Drive Setup
To enable automatic uploads:
1. Click "Connect" in the Google Drive status area
2. Authorize with your Google account
3. Check "Auto-upload to Google Drive" when exporting
4. Files are saved with timestamp: `silver-fox-order-YYYY-MM-DD-HH-MM-SS.csv`

## 💡 Usage Tips

### Efficient Data Entry (NEW Workflow in v2.1)
1. **Select Type**: Choose windshield/body-side/complement type (locks with green indicator)
2. **Select Size**: Size dropdown appears and locks when selected
3. **Select Material**: Material dropdown appears and locks when selected  
4. **Enter Text**: Text fields appear with "Enter Multiple Items" button
5. Use keyboard shortcuts for spreadsheet-like navigation
6. Duplicate similar rows with `Ctrl + D`
7. Drag rows to reorder as needed

### Bulk Orders
1. Complete all three locking steps (Type → Size → Material)
2. Click "Enter Multiple Items" when button becomes available
3. Material column removed from modal (uses locked value)
4. Use Tab/Enter to navigate between cells
5. Apply all entries with `Ctrl + Enter`
6. Export directly from the modal

### Field Unlocking
- Click "Change type/size/material" links in green locked indicators
- Unlocking resets subsequent fields (unlocking Size resets Material and Text)
- Confirmation dialog prevents accidental changes

## 🏢 About Silver Fox Marketing
Professional vehicle merchandising and graphics solutions for automotive dealerships in the St. Louis area.

## 📞 Support
For technical support or feature requests, contact Silver Fox Marketing STL.

---

**Version:** 2.1  
**Last Updated:** August 2025  
**License:** Proprietary - Silver Fox Marketing STL

## 🆕 Version 2.1 Changelog

### Major Enhancements
- **Complete Field Locking System**: Type, Size, and Material all lock with visual indicators
- **Sequential Field Revelation**: Form guides users through proper order (Type → Size → Material → Text)
- **Windshields Modal Optimization**: Material dropdown removed (uses locked value)
- **Enhanced Flyout Support**: Proper 4-field layout (Flyout 1, Mainline 1, Mainline 2, Misc)
- **Improved CSV Export**: Dynamic headers for Flyout vs Standard windshields

### Technical Improvements  
- **JavaScript Handler Functions**: Complete rewrite for proper field sequencing
- **Modal Title Enhancement**: Shows locked Size and Material values
- **Data Consistency**: Locked values properly flow through all workflows
- **VersaWorks Compatibility**: Static selections prevent processing errors

### Product Type Updates
- **Complements**: Upper-Triangle option removed (Inverted-Triangle and Oval-Comp only)
- **All Types**: Material now required and locked selection
- **Windshields**: Upper-Triangle still available for windshield types