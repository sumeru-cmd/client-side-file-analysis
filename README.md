# Client-Side File Analysis (Exiffshield)

A 100% client-side browser-based forensic tool and image metadata stripper built with HTML, JavaScript, and Tailwind CSS. It checks file encodings and headers to confirm files match their expected formats safely in the browser.

## Features

- **Magic Byte Inspection:** Reads raw file headers to detect extension spoofing (e.g., checking if a `.jpg` or `.pdf` file has been disguised).
- **Heuristic PDF Scan:** Looks for embedded active script markers (`/JavaScript`, `/OpenAction`).
- **EXIF Detection & Stripping:** Identifies EXIF/GPS blocks in JPEG files and lets you safely clean and download them.

## How to Run

1. Clone the repository and navigate into it:
   ```bash
   git clone [https://github.com/sumeru-cmd/client-side-file-analysis.git](https://github.com/sumeru-cmd/client-side-file-analysis.git)
   cd client-side-file-analysis
