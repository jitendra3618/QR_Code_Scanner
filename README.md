# QR_Code_Scanner

Live link https://jitendra3618.github.io/QR_Code_Scanner/


<h1>Overview</h1>
This project is a simple QR Code Scanner web application that allows users to decode QR codes using their browser. The application provides two options for scanning QR codes:

Upload Image: Users can upload an image file containing a QR code to be scanned.<br>
Camera Scan: Users can use the camera of their system to scan QR codes in real-time.<br>
The decoded text of the scanned QR code is then displayed to the user through an alert message.<br>

<h1>Features</h1>
Upload Image: Allows users to upload an image file for QR code scanning.<br>
Camera Scan: Enables real-time QR code scanning using the system's camera.<br>
Alert Message: Displays the decoded text of the scanned QR code in an alert message.<br>
<h1>Technologies Used</h1>
HTML: Markup language for creating the structure of the web pages.<br>
CSS: Stylesheet language for designing the visual presentation.<br>
JavaScript: Programming language for implementing the QR code scanning functionality.<br>

Usage
<br>Upload Image:<br>

Click on the "Upload Image" button.<br>
Choose an image file containing a QR code.<br>
Click "Scan" to decode the QR code.<br>
Camera Scan:<br>

Click on the "Camera Scan" button.<br>
Allow the browser to access your camera.<br>
Align the QR code within the camera view to decode it.
Alert Message:<br>

After scanning, an alert message will display the decoded text.
<h1>Demo</h1>
(https://github.com/jitendra3618/QR_Code_Scanner/files/14000632/Jitendra_Resume.docx)


https://github.com/jitendra3618/QR_Code_Scanner/assets/137607500/f12b2f0b-309b-4a50-8748-544fffc3e986

HTML5-qrcode library methods:<br>
Html5QrcodeScanner: Initializes the QR code scanner.<br>
render(): Renders the scanner within a specified HTML element.<br>
onScanSuccess(decodeText, decodeResult): A callback function triggered upon successful QR code scanning, displaying decoded text in an alert.<br>
fps: Sets the frames per second for video capture.<br>
qrbos: Sets the QR code detection boundary size.<br>
