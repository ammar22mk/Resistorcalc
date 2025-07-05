# Advanced Resistor Color Code Calculator

This is a web-based, interactive resistor color code calculator that supports 3, 4, 5, and 6-band resistors. It provides a user-friendly interface with an SVG-based resistor illustration, allowing users to click on the bands to select colors and see the resistance, tolerance, and TCR values calculated in real-time.

 <!-- Replace with a real screenshot URL -->

### ✨ [Live Demo](https://your-username.github.io/your-repo/) <!-- Replace with your live demo link -->

---

## Features

- **Multiple Band Support**: Accurately calculates values for 3, 4, 5, and 6-band resistors.
- **Interactive SVG Resistor**: A clean, scalable vector graphic of a resistor where you can click each band to change its color.
- **Intuitive Color Palette**: A pop-up color palette makes selecting colors for each band quick and easy.
- **Real-time Calculation**: Resistance, tolerance, and Temperature Coefficient of Resistance (TCR) are updated instantly as you change colors.
- **Dynamic UI**: The interface adapts based on the number of bands selected, showing or hiding the tolerance and TCR values as needed.
- **Smart Formatting**: Resistance values are automatically formatted into kΩ, MΩ, GΩ, and mΩ for better readability.
- **Pure JavaScript**: Built with vanilla JavaScript, HTML, and CSS—no external libraries or frameworks needed.
- **Responsive Design**: The layout is functional and looks great on both desktop and mobile devices.

---

## How to Use

1.  **Open `index.html`** in your web browser or visit the [live demo](#).
2.  **Select the number of bands** (3, 4, 5, or 6) using the radio buttons at the top.
3.  **Click on a color band** on the resistor diagram.
4.  **Choose a new color** from the color palette that appears.
5.  The **resistance value**, **tolerance**, and **TCR** (for 6-band resistors) will be displayed automatically below the resistor.

---

## Project Files

-   **`index.html`**: The main HTML file containing the structure of the calculator, including the SVG for the resistor.
-   **`style.css`**: The stylesheet that provides the visual design, layout, and responsiveness for the application.
-   **`script.js`**: The core JavaScript file that handles all the logic, including:
    -   State management for the resistor's bands and colors.
    -   Calculation logic for resistance, tolerance, and TCR.
    -   DOM manipulation to update the UI and handle user interactions.
    -   Displaying and managing the color palette.

---

## Technologies Used

-   **HTML5**: For the structure and content.
-   **CSS3**: For styling and responsive design.
-   **JavaScript (ES6+)**: For all the application logic and interactivity.

---

## Author

-   **[ammar22mk](https://github.com/ammar22mk)**