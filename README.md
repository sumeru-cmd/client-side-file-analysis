# client-side-file-analysis
html project that checks the encoding of received and anticipated file to confirm it is the expected file
Exiffshield
A 100% client-side browser-based forensic tool and image metadata stripper built with HTML, JavaScript, and Tailwind CSS.

## Features
- **Magic Byte Inspection:** Reads raw file headers to detect extension spoofing (e.g., checking if a `.jpg` or `.pdf` file has been disguised).
- **Heuristic PDF Scan:** Looks for embedded active script markers (`/JavaScript`, `/OpenAction`).
- **EXIF Detection & Stripping:** Identifies EXIF/GPS blocks in JPEG files and lets you safely clean and download them directly in the browser.

## Usage
Simply open `index.html` in any web browser, or host it live instantly using GitHub Pages.
