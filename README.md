# QR_Code_Scanner

Live link https://jitendra3618.github.io/QR_Code_Scanner/


Overview
This project is a simple QR Code Scanner web application that allows users to decode QR codes using their browser. The application provides two options for scanning QR codes:

Upload Image: Users can upload an image file containing a QR code to be scanned.
Camera Scan: Users can use the camera of their system to scan QR codes in real-time.
The decoded text of the scanned QR code is then displayed to the user through an alert message.

Features
Upload Image: Allows users to upload an image file for QR code scanning.
Camera Scan: Enables real-time QR code scanning using the system's camera.
Alert Message: Displays the decoded text of the scanned QR code in an alert message.
Technologies Used
HTML: Markup language for creating the structure of the web pages.
CSS: Stylesheet language for designing the visual presentation.
JavaScript: Programming language for implementing the QR code scanning functionality.

Usage
Upload Image:

Click on the "Upload Image" button.
Choose an image file containing a QR code.
Click "Scan" to decode the QR code.
Camera Scan:

Click on the "Camera Scan" button.
Allow the browser to access your camera.
Align the QR code within the camera view to decode it.
Alert Message:

After scanning, an alert message will display the decoded text.
Demo
(https://github.com/jitendra3618/QR_Code_Scanner/files/14000632/Jitendra_Resume.docx)


https://github.com/jitendra3618/QR_Code_Scanner/assets/137607500/f12b2f0b-309b-4a50-8748-544fffc3e986

HTML5-qrcode library methods:
Html5QrcodeScanner: Initializes the QR code scanner.
render(): Renders the scanner within a specified HTML element.
onScanSuccess(decodeText, decodeResult): A callback function triggered upon successful QR code scanning, displaying decoded text in an alert.
fps: Sets the frames per second for video capture.
qrbos: Sets the QR code detection boundary size.
