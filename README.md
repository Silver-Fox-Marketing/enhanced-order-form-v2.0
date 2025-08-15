# Enhanced Order Form v2.2

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

### 🔒 Lock Icon System (ENHANCED in v2.2)
- **Interactive Lock Icons**: Professional lock icons appear next to locked fields
- **Simultaneous Field Display**: All three fields (Type, Size, Material) appear at once
- **Visual Field States**: Locked fields are visually grayed out and disabled
- **Click-to-Unlock**: Lock icons show confirmation dialog when clicked
- **VersaWorks Compatibility**: Static selections prevent accidental changes

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
- **Lock Icon Interface** - Professional, intuitive field locking with visual feedback
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

### Efficient Data Entry (ENHANCED in v2.2)
1. **Select Type**: Choose windshield/body-side/complement type (all fields appear, lock icon shows)
2. **Select Size**: Lock icon appears next to size field when selected
3. **Select Material**: Lock icon appears next to material field when selected  
4. **Enter Text**: Text fields appear with "Enter Multiple Items" button
5. **Unlock Fields**: Click lock icons to change selections (shows confirmation dialog)
6. Use keyboard shortcuts for spreadsheet-like navigation
7. Duplicate similar rows with `Ctrl + D`
8. Drag rows to reorder as needed

### Bulk Orders
1. Complete all three locking steps (Type → Size → Material)
2. Click "Enter Multiple Items" when button becomes available
3. Material column removed from modal (uses locked value)
4. Use Tab/Enter to navigate between cells
5. Apply all entries with `Ctrl + Enter`
6. Export directly from the modal

### Field Unlocking
- Click lock icons next to locked fields
- Confirmation dialog prevents accidental changes
- Unlocking resets subsequent fields and clears bulk data
- Lock icons provide visual feedback with hover effects

## 🏢 About Silver Fox Marketing
Professional vehicle merchandising and graphics solutions for automotive dealerships in the St. Louis area.

## 📞 Support
For technical support or feature requests, contact Silver Fox Marketing STL.

---

**Version:** 2.2  
**Last Updated:** August 2025  
**License:** Proprietary - Silver Fox Marketing STL

## 🆕 Version 2.2 Changelog (Latest)

### 🔒 Major UX Enhancement - Lock Icons Implementation
- **Lock Icon Interface**: Replaced green notification boxes with professional lock icons
- **Simultaneous Field Display**: All three fields (Type, Size, Material) appear at once
- **Interactive Lock Icons**: Clickable icons with hover effects and smooth animations
- **Visual Field States**: Locked fields are grayed out and clearly disabled
- **Improved Workflow**: No more sequential field revelation - much faster form completion

### ✨ Technical Improvements
- **Modern CSS Implementation**: Added `.field-container` and `.lock-icon` styling
- **JavaScript Refactor**: Updated all handler functions to use CSS classes instead of DOM manipulation
- **Enhanced User Feedback**: Lock icons provide immediate visual confirmation
- **Accessibility Improvements**: Better visual indicators for field states
- **Performance**: Removed dependency on legacy DOM elements

### 🎯 User Experience Benefits
- **Faster Form Completion**: See all required fields immediately
- **Professional Interface**: Clean, modern lock icons replace bulky notification boxes  
- **Intuitive Interaction**: Click lock to unlock with confirmation dialog
- **Consistent Behavior**: All product types (Windshields, Body Sides, Complements) work identically
- **Clear Visual Hierarchy**: Locked vs unlocked states are immediately apparent

---

## 📋 Version 2.1 Changelog

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