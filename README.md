# Captcha Solver Interface

A simple, responsive single-file HTML application demonstrating a human-powered captcha solver interface using Tailwind CSS. This application allows users to view a captcha image and input their perceived solution. It supports loading captcha images from a URL query parameter or defaults to a local sample image.

## Features

*   **Responsive Design:** Built with Tailwind CSS, ensuring a consistent and user-friendly experience across various screen sizes.
*   **Dynamic Image Loading:** Loads captcha images based on a `url` query parameter (e.g., `index.html?url=https://example.com/captcha.png`).
*   **Default Captcha:** If no `url` parameter is provided, it defaults to displaying `sample.png`.
*   **User Input & Submission:** Provides an input field for the user to type the captcha text and a button to submit their answer.
*   **Client-Side Validation (for sample.png):** For the default `sample.png`, it includes a hardcoded solution for client-side verification.
*   **Professional UI:** Clean and modern interface powered by Tailwind CSS.

## Usage

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.
2.  **Default Captcha:** By default, the application will display `sample.png`. You can attempt to solve it (the solution for `sample.png` is "ADGR3").
3.  **Load External Captcha:** To load an external captcha image, append a `?url=` query parameter to the URL in your browser's address bar.
    *   Example: `file:///path/to/your/index.html?url=https://example.com/path/to/your/captcha.png`
    *   (Note: For `file://` URLs, external image loading might be restricted by browser security policies like CORS. It generally works better when served from a web server.)

## Development

This is a single-file application. No build steps are required. Just open `index.html` in a web browser.

### Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** Utility-first CSS framework for styling.
*   **JavaScript:** For dynamic image loading and client-side interaction.

## License

This project is licensed under the MIT License. See the `LICENSE` file for full details.
