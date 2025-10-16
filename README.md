# Sales Total Calculator

## Summary
This static HTML page displays the total sum of the 'Sales' column from a dataset. It reads predefined CSV data and computes the total sales amount, presenting the result directly on the webpage.

## Setup
Since this is a static HTML file, setting up and running the application is straightforward:

1. Download or clone the repository containing the `index.html` file.
2. Open the `index.html` file in any modern web browser.
3. The total sales figure will be displayed automatically on the page.

## Code Explanation
The application consists of a simple HTML structure with embedded JavaScript:

- The CSV data is hardcoded within the script as a string.
- The script splits the data into lines and processes the header to identify the 'Sales' column index.
- It iterates through each data row, parsing the 'Sales' values and accumulating the total.
- The total result is then displayed inside the `<div id="total-sales">`.

This approach allows the page to operate independently as a static file without requiring server-side processing.

## License
This project is licensed under the MIT License. See the [`LICENSE`](LICENSE) file for details.