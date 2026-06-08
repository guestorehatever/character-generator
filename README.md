# Teletext Editor

A realistic, fully-featured teletext emulator with complete editing capabilities, page management, and HTML export functionality.

## Features

- **Realistic Teletext Display**: Authentic 40x24 character grid with CRT scanlines and green phosphor glow
- **Full Editing Capabilities**: Edit text, colors, and page content in real-time
- **Page Management**: Create and navigate between pages (100-899)
- **Color System**: 8 classic teletext colors with custom color picker support
- **Character Palette**: Quick access to common characters
- **Keyboard Navigation**: Arrow keys for navigation, Delete to clear
- **Save as HTML**: Export pages as standalone, full-screen HTML files
- **Import/Export**: Save and load pages as JSON

## Usage

### Basic Editing

1. **Click a cell** to select it
2. **Type a character** or use the character palette to insert text
3. **Select colors** from the foreground/background palettes
4. **Navigate** with arrow keys or click cells directly

### Page Navigation

- Use **Page Number** input to jump to a specific page (100-899)
- Use **← PREV** and **NEXT →** buttons to move between pages
- Each page maintains its own content

### Exporting

- **Save as HTML**: Creates a standalone HTML file with full-screen display
- **Export JSON**: Saves all pages as JSON for backup/sharing
- **Import JSON**: Loads previously saved pages

### Keyboard Shortcuts

- **Arrow Keys**: Navigate between cells
- **Delete/Backspace**: Clear current cell
- **Type**: Insert character into selected cell

## Technical Details

- **Grid**: 40 columns × 24 rows (standard teletext format)
- **Colors**: 8 classic teletext colors (Black, Red, Green, Yellow, Blue, Magenta, Cyan, White)
- **Font**: Monospace (Courier New) for authentic appearance
- **Effects**: CRT scanlines, phosphor glow, authentic green-on-black display

## File Structure

- `index.html` - Complete application (HTML, CSS, JavaScript)

## Browser Compatibility

Works on all modern browsers (Chrome, Firefox, Safari, Edge)