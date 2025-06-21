# QR-Code-Generator


## Project Overview

QR Code Generator is a simple yet powerful tool that converts user input (like URLs, text, or contact details) into QR codes. These codes can be scanned using any standard QR code reader or mobile camera, making data sharing easy and efficient.


## Key Features
- Generate QR codes from:
- - URLs
  - Plain text
  - Emails or contact info
- Save QR codes as image files
- Fast, lightweight, and beginner-friendly
- Option to customize size and color (optional)


## Librari Used:
- `pyqrcode` - used to create QR codes.
- `pypng` - creating PNG images.
- `pyqrcode` uses `pypng` to save the QR code as a .png file.


```bash
!pip install pyqrcode pypng
```


![image](https://github.com/user-attachments/assets/80fcf445-ac31-4cfa-bff7-518441a2cec1)

## How It Works
1. Input Data
- Accept any string input from the user:
- - URLs
  - Custom text
  - Contact info

2. QR Code Generation
- Use the pyqrcode` library to convert the text into a QR code matrix.

3. Save or Display
- The QR is saved as a PNG or JPEG image.
- Can be previewed or used in print/online.






