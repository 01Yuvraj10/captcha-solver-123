# Captcha Solver Interface Demo

This project provides a simple, single-file front-end web application that serves as an interface for interacting with captcha images. It allows users to load captcha images either from a default local file or a specified URL, and then input their perceived solution.

**Note**: This is a purely client-side demonstration of an interface. It does **not** contain any actual captcha-solving logic (e.g., OCR or AI algorithms) on the front-end. The "solver" aspect refers to the user manually entering the solution.

## Features

*   **Responsive Design**: Built with Tailwind CSS for a mobile-first, responsive user interface.
*   **Load Image from URL**: Users can input an image URL to dynamically load a captcha image.
*   **URL Parameter Support**: The application can automatically load an image if its URL is provided as a `?url=` query parameter in the browser's address bar (e.g., `index.html?url=https://example.com/some-captcha.png`).
*   **Default Image**: If no URL is provided, it defaults to displaying `sample.png`.
*   **Solution Input**: A text field to enter the captcha solution.
*   **Submission Feedback**: Provides basic feedback on submission (without actual validation).

## Technologies Used

*   **HTML5**: For the core structure of the web page.
*   **Tailwind CSS**: A utility-first CSS framework for styling and responsiveness.
*   **JavaScript**: For handling dynamic image loading and form submission logic.

## Setup and Usage

1.  **Save the files**: Ensure `index.html` and `sample.png` are in the same directory.
2.  **Open in Browser**: Simply open the `index.html` file in your web browser.
3.  **Load a Captcha (Optional)**:
    *   **Using the URL input**: Enter an image URL into the provided input field and click "Load".
    *   **Using a URL parameter**: Append `?url=YOUR_IMAGE_URL` to the `index.html` URL in your browser's address bar (e.g., `file:///path/to/your/index.html?url=https://example.com/captcha.png`).
4.  **Enter Solution**: Type your captcha solution into the designated input field.
5.  **Submit**: Click the "Submit Solution" button. The solution will be logged to the console and displayed as feedback on the page.

## Example Image

The default captcha image `sample.png` is an example of a stylized text captcha that reads "ADUR3".

<img src='sample.png' alt='Sample Captcha' width='200'>

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.