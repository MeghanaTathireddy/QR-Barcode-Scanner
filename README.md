# QR-Barcode-Scanner
This is a real-time desktop application built with Python, OpenCV, and Pyzbar that uses your webcam to detect and decode QR codes and barcodes. It highlights detected codes on the video feed and allows users to click on QR code regions to automatically open URLs in their browser.

Project Overview
Detects and decodes barcodes and QR codes from webcam input.

Draws bounding boxes and overlays decoded text on the video stream.

Supports clickable regions: If a QR code contains a URL, clicking on it will open the link in the default browser.

Ideal for lightweight local use — no internet or server required.

Tech Stack
Language: Python 3.x

Libraries Used:

OpenCV

Pyzbar

NumPy

Webbrowser (built-in Python module)

System Requirements
Python 3.x installed

Webcam connected to your system

Windows, macOS, or Linux

Installation Instructions
Clone this repository:

bash
Copy
Edit
git clone https://github.com/MeghanaTathireddy/QR-Barcode-Scanner.git
cd QR-Barcode-Scanner
Install the required packages:

nginx
Copy
Edit
pip install opencv-python pyzbar numpy
How to Run the Project
Open a terminal in the project folder.

Run the Python script:

scss
Copy
Edit
python barcode(detection_and_decoding).py
The webcam will open automatically, and the app will start scanning for QR/barcodes.

Click on a QR code area to open its link in your browser.

Press c to capture the detected data in the terminal.

Press q to exit the app.

Author
Meghana Tathireddy

GitHub: https://github.com/MeghanaTathireddy

LinkedIn: https://www.linkedin.com/in/meghana-reddy-tathireddy

License
This project is licensed under the MIT License: https://opensource.org/licenses/MIT
