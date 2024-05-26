# url_to_QRcode

Description

This project is a simple Node.js application that converts a user-entered URL into a QR code image and saves it along with the URL in a text file. The application leverages the inquirer package to get user input, the qr-image package to generate the QR code, and the native fs (file system) module to save the QR code image and URL.

Features

    Prompts the user to input a URL.
    Generates a QR code image from the entered URL.
    Saves the generated QR code image as qr_img.png.
    Writes the entered URL to a text file named URL.txt.

Getting Started
1) Clone the repository
2) Install the dependencies: npm install / npm i
3) Run the application: nodemon index.js / node index.js
4) Enter the URL when prompted: Type in your URL: https://example.com

After entering the URL, the application will:

    Generate a QR code image (qr_img.png) in the project directory.
    Save the entered URL to a text file (URL.txt) in the project directory.
    Display a success message: The file has been saved!
    qr_img.png - The QR code image representing the entered URL.
   
