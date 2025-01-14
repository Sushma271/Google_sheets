# Google_sheets

A simple, interactive spreadsheet web app built using HTML5, JavaScript, and the `<canvas>` element. The app mimics basic spreadsheet functionality, allowing users to edit, navigate, and perform simple functions like sum, average, minimum, and maximum on cell ranges.

## Features

- **Spreadsheet Grid**: Fully interactive grid of cells with the ability to select individual cells or ranges.
- **Cell Editing**: Click on a cell and edit its contents.
- **Formula Support**: Basic formulas like `SUM`, `AVERAGE`, `MIN`, and `MAX` for cell ranges (e.g., `=SUM(A1:A3)`).
- **Cell Navigation**: Navigate between cells using arrow keys.
- **Highlighting Cells**: Highlight selected cells or ranges for better visibility.
- **Responsive Design**: Adjusts to different screen sizes.
- **Real-time Updates**: Changes made to a cell (data or formula) are reflected in real-time on the grid.

## Technologies Used

- **HTML5**: For creating the structure of the spreadsheet.
- **CSS**: For styling the app and cells of the spreadsheet.
- **JavaScript**: For functionality, including cell navigation, editing, and formulas.
- **Canvas API**: To draw and manage the grid and cells dynamically.

## Getting Started

### Prerequisites

- A modern web browser with JavaScript enabled.
- No server or backend required; everything runs client-side.

### Installation

1. Clone or download the repository to your local machine:
   ```bash
   git clone https://github.com/Sushma271/Google_sheets

2. open index.html

## How to Use

1. **Select a Cell**: Click any cell to select it.
2. **Edit a Cell**: Type your desired value in the text input field, then press Enter to update the cell.
3. **Navigate Between Cells**: Use arrow keys (`←`, `→`, `↑`, `↓`) to navigate between cells.
4. **Formulas**: To perform basic calculations, enter a formula in a cell, e.g., `=SUM(A1:A3)` to sum the values from A1 to A3.
5. **Highlight Cells**: Click a cell to highlight it or select a range of cells.
6. **Grid Visualization**: The app displays borders and highlights selected cells and ranges.

## Supported Functions

- **SUM**: `=SUM(A1:A3)` — Sums the values in the specified range.
- **AVERAGE**: `=AVERAGE(A1:A3)` — Calculates the average of the values in the specified range.
- **MIN**: `=MIN(A1:A3)` — Finds the minimum value in the specified range.
- **MAX**: `=MAX(A1:A3)` — Finds the maximum value in the specified range.

