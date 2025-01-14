# Google Sheet

This project is a simplified clone of Google Sheets, implemented using HTML, CSS, and JavaScript. It provides basic spreadsheet functionality with a user-friendly interface.

## Features

- Multiple sheets support
- Cell formatting options (font family, font size, bold, italic, underline)
- Text alignment (left, center, right)
- Text and background color customization
- Formula bar for cell content
- Download and upload functionality

## File Structure

- `index.html`: Main HTML file containing the structure of the application
- `style.css`: CSS file for styling the application
- `script.js`: JavaScript file for core functionality and cell state management
- `sheet.js`: JavaScript file for sheet-related operations
- `functionalities.js`: JavaScript file for various UI functionalities (not provided in the attachment)

## Usage

1. Open `index.html` in a web browser to launch the application.
2. Use the top menu to access different formatting options.
3. Click on cells to edit their content.
4. Use the formula bar to view or edit the content of the selected cell.
5. Create new sheets using the "+" button in the bottom-left corner.
6. Switch between sheets by clicking on the sheet tabs at the bottom.

## Key Components

### Header

- File menu (non-functional in this version)
- Home menu (active by default)
- Cell styling options (font, size, bold, italic, underline, alignment, colors)
- Download and upload buttons

### Grid

- Spreadsheet grid with columns A-Z and rows 1-100
- Editable cells with formatting support

### Footer

- New sheet creation button
- Sheet navigation tabs

## JavaScript Functionality

- `script.js`: Manages cell states, active sheet, and core spreadsheet functionality
- `sheet.js`: Handles sheet creation, switching, and updating cell data across sheets
- `functionalities.js`: Implements various UI interactions and formatting options (file not provided)

## Styling

The `style.css` file provides a clean, modern look reminiscent of Google Sheets, with a green accent color for the main menu.

## Future Enhancements

- Implement formula calculation
- Add more formatting options (borders, merging cells, etc.)
- Improve performance for larger spreadsheets
- Implement real-time collaboration features

## Contributing

Contributions to improve the functionality or fix bugs are welcome. Please fork the repository and create a pull request with your changes.

## License

This project is open-source and available under the MIT License.
