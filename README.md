# Captcha Challenge Frontend

This project provides a simple, single-file responsive HTML application designed to present a captcha challenge to the user. It leverages Tailwind CSS for styling and includes basic JavaScript to handle image loading and user input.

## Features

*   **Responsive Design:** Built with Tailwind CSS, ensuring a consistent experience across various devices and screen sizes.
*   **Dynamic Image Loading:** The captcha image source can be specified via a URL query parameter (`?url=https://example.com/captcha.png`).
*   **Default Captcha Image:** If no URL parameter is provided, it defaults to the `sample.png` file included in the project.
*   **User Input Field:** A dedicated input field for users to enter their solution.
*   **Client-Side Submission:** A basic client-side submission mechanism is included, demonstrating how user input would be captured. (Note: Actual captcha verification typically requires a backend server.)

## Getting Started

To run this application, simply open the `index.html` file in your web browser. Ensure that `sample.png` is in the same directory as `index.html`.

### Usage

1.  **Open `index.html`:** Navigate to the `index.html` file in your browser.
2.  **Default Image:** By default, the `sample.png` image will be displayed.
3.  **Custom Captcha Image:** To display a different captcha image, append a `?url=` query parameter to the URL in your browser's address bar.
    *   Example: `file:///path/to/your/project/index.html?url=https://example.com/another_captcha.png`
    *   (Note: Due to browser security restrictions, direct file URL access to external images might be blocked, depending on your browser and local setup. For external URLs, hosting this on a web server is recommended.)
4.  **Enter Solution:** Type your solution into the provided text field.
5.  **Submit:** Click the "Submit" button or press Enter to see your input registered.

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** Utility-first CSS framework for styling.
*   **JavaScript:** For dynamic behavior, including image loading and input handling.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
