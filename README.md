## QR Code Generator
This is a simple QR Code Generator built using HTML, CSS, and JavaScript. It allows users to generate QR codes by entering text or URLs. The QR codes are generated using an external API and are displayed dynamically on the webpage.

## Features
Responsive Design: The layout is responsive and adjusts for different screen sizes using a viewport meta tag.
Easy Input: Users can enter any text or URL to generate a corresponding QR code.
QR Code Generation: The app uses the qrserver API to create the QR code image, which is displayed in real-time.
Error Handling: If the input field is empty, the input box shakes to indicate an error.

## How It Works
The user enters text or a URL in the input field.
Upon clicking the "Generate QR Code" button, a request is made to the qrserver API to generate a QR code based on the input.
The generated QR code is displayed inside the container below the input field.
If the input field is left empty, a shaking animation indicates that input is required.

## Technologies Used
HTML: For structuring the webpage.
CSS: For styling the page and adding animations.
JavaScript: For handling the QR code generation and error handling.
qrserver API: To generate the QR code based on the user input.

## How to Use
Clone the repository to your local machine.
Open the index.html file in your browser.
Enter the text or URL in the input field and click "Generate QR Code."
The generated QR code will appear in the box below the input field.
