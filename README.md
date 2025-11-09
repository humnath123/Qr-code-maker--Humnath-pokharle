# QR Code Generator

A simple Python script to generate and display QR codes using the `qrcode` and `Pillow` libraries.

## Features
- Generate QR codes from any text or number
- Save QR code as a PNG image
- Display the QR code automatically

## Requirements
- Python 3.x
- `qrcode` library
- `Pillow` library

## Installation
```bash
pip install qrcode[pil]
```

## Usage
1. Clone or download this repository.
2. Run the script:
   ```bash
   python generate_qr.py
   ```
3. The QR code will be saved as `qrcode.png` and displayed.

## Customization
- Change the `data` variable in the script to generate a QR code for different content.
- Adjust `version`, `error_correction`, `box_size`, and `border` for different QR code styles.
