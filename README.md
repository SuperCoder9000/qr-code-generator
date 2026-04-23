# QR Code Generator (Node.js CLI)

A simple and practical QR Code Generator built using Node.js. This project allows users to convert any URL into a QR code image directly from the terminal, while also saving the input for future reference.

---

## Overview

This application:

* Accepts a URL as input through the command line
* Generates a QR code image (`qr_img.png`)
* Stores the entered URL in a text file (`URL.txt`)

It is designed to be lightweight and focused, demonstrating core Node.js concepts such as user input handling, file operations, and third-party package integration.

---

## Tech Stack

* Node.js
* Inquirer (CLI input handling)
* qr-image (QR code generation)
* fs module (file system operations)

---

## Project Structure

```id="1e2x9f"
├── index.js
├── package.json
├── package-lock.json
└── .gitignore
```

---

## Installation

1. Clone the repository:

```bash id="c2d9sa"
git clone https://github.com/your-username/qr-code-generator.git
cd qr-code-generator
```

2. Install dependencies:

```bash id="u2k91p"
npm install
```

---

## Usage

Run the application using:

```bash id="u8sd2k"
node index.js
```

Enter a URL when prompted. The application will:

* Generate a QR code image (`qr_img.png`)
* Save the input URL to `URL.txt`

---

## Example

```id="h72kda"
Type in your URL: https://example.com
```

---

## Requirements

* Node.js v18 or higher

---

## Notes

* The `node_modules` directory is excluded from version control
* Dependencies are managed through `package.json` and `package-lock.json`

---

## Future Improvements

* Support for additional output formats (SVG, JPG)
* Customization options (color, size, error correction level)
* Web-based interface

---

## License

This project is licensed under the ISC License.

---

## Author

[Your Name]

---

## Summary

This project serves as a foundational implementation of a CLI-based tool in Node.js, combining user interaction, file handling, and external libraries into a cohesive application.
