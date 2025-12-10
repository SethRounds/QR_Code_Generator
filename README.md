# QR_Code_Generator

A small static QR code generator page you can host directly with GitHub Pages.

Live preview (after enabling GitHub Pages):
https://SethRounds.github.io/QR_Code_Generator

Features
- Enter a line of text or a URL and generate a QR code.
- Download the generated QR code as a PNG image.
- Fully static — no server code required.

How it works
- The page uses the QRCode.js library (served from CDNJS) to render a QR code in the browser.
- The download button grabs the image/canvas data URL and triggers a client-side download.

Files added
- index.html — the static page and client logic
- style.css — simple styling
- README.md — this file

Libraries used
- QRCode.js (qrcodejs) from https://cdnjs.com/libraries/qrcodejs (CDNJS)

Testing instructions
1. Open index.html in a browser or visit the GitHub Pages URL once published.
2. Enter several inputs (examples below) and click Generate.
3. Click Download PNG and confirm the downloaded image contains the QR code.

Example inputs tested
- https://www.google.com
- https://github.com/SethRounds/QR_Code_Generator
- Hello, world!
- Email: test@example.com

Notes
- If the download button is disabled, generate a QR code first.
- If the library produces an <img> or <canvas>, the download will work. Some fallback cases may not be downloadable in older browsers.
