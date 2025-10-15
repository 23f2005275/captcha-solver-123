# Captcha Solver Application

This is a simple, single-file responsive HTML application designed to simulate a captcha solving process. It uses Tailwind CSS for styling and vanilla JavaScript for interactivity.

## Features

*   **Responsive Design**: Adapts to various screen sizes using Tailwind CSS.
*   **Dynamic Image Loading**: Loads captcha images from a specified URL parameter `url` or defaults to a local image.
*   **Client-Side Verification**: Simulates captcha verification against a hardcoded value ("ADUR3") derived from the provided `sample.png`.

## Usage

1.  **Open `index.html` in your web browser.**
2.  **Default Captcha**: By default, the application will display `sample.png`. To verify this captcha, enter "ADUR3" into the input field.
3.  **Custom Captcha Image (via URL)**: You can pass an image URL as a query parameter `url`.
    *   **Example**: `index.html?url=https://example.com/some-captcha.png`
    *   *Note*: For custom images loaded via URL, the client-side verification will still expect "ADUR3" unless the JavaScript code is modified. This application primarily demonstrates the display and input mechanism.

## Development

This project is a single-file HTML application. You can open `index.html` directly in any modern web browser to run it.

### Technologies Used

*   **HTML5**: Provides the structural foundation of the application.
*   **Tailwind CSS**: A utility-first CSS framework used for rapid and responsive UI development.
*   **JavaScript (Vanilla)**: Handles dynamic image loading, user input, and client-side captcha verification logic.

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.