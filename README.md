# Advanced Color Picker

An interactive color picker tool built with HTML, CSS, and JavaScript. This tool allows users to select colors, view complementary colors, save recent selections, and reset to the default color.

---

## Features
- **Color Picker**: Select colors using a built-in color input field.
- **Complementary Color Display**: Automatically shows the complementary color of the selected color.
- **Recent Colors**: Keeps a history of the last 5 selected colors, displayed as clickable swatches.
- **Reset Button**: Resets the color picker to white (`#ffffff`).
- **Live Preview**: Displays the selected color and complementary color side by side.

---

## Technologies Used
- **HTML5**: Structure of the tool.
- **CSS3**: Styling and layout.
- **JavaScript**: Functionality for dynamic color updates and interactions.

---

## How to Use
1. Download the files and open the `index.html` file in a browser.
2. Select a color using the color picker.
3. View the selected color and its complementary color in real-time.
4. Use the recent color swatches to quickly pick a previously selected color.
5. Click "Reset" to return the picker to the default color.

---

## Code Overview

### **HTML**
```html
<input type="color" id="color-picker" value="#ffffff">
<div id="color-display"></div>
<div id="complementary-display"></div>
````
