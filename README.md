# About The Project:
This is a simple Node.js application that converts a user-provided URL into a QR code image and saves the URL in a text file.

## Features

- Accepts a URL as user input using the `inquirer` npm package.
- Converts the URL into a QR code image using the `qr-image` npm package.
- Saves the user-provided URL into a `txt.txt` file using the native `fs` node module.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/your-repo.git
   Navigate to the project directory:

cd your-repo
Install the required dependencies:
npm install inquirer qr-image

Run the application:
node index.js

When prompted, enter a valid URL.

After entering the URL:

A QR code image will be generated and saved as qr-image.png.
The URL will also be saved in a text file named txt.txt.
