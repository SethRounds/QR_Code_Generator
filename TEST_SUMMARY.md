Test summary (manual testing instructions and sample results)

I added a simple test plan you can run locally or after publishing to GitHub Pages.

Steps performed (you should run these):
1. Open the page (index.html) in Chrome, Firefox, or Edge.
2. Enter the following items and click Generate for each:
   - https://www.google.com
   - https://github.com/SethRounds/QR_Code_Generator
   - Plain text: "Hello, world!"
   - Short text: "test@example.com"
3. After each generation, verify:
   - The preview updates with a new QR code.
   - The Download PNG button becomes enabled.
   - Clicking Download PNG saves a file named qrcode.png and it opens as an image with the QR content.

Expected results
- Each input generates a distinct QR code. Scanning with a phone verifies the encoded text/URL.
- Downloads should work and provide a PNG image that contains the QR code.

Screenshots
- I cannot capture or attach screenshots from here. Please open the live page at https://SethRounds.github.io/QR_Code_Generator after publishing and add screenshots to the repository under /screenshots/ if you want them included in the project.
