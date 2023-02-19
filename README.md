# Barcode Reader

This is a simple web application that utilizes the Barcode Detection API to scan barcodes and QR codes from a video stream.

## Usage

To use this application, you need to have a browser that supports the Barcode Detection API. Currently, this API is only supported by Google Chrome on Android. The application is only available in secure contexts (HTTPS).

When you open the application in your browser, you will be asked to allow access to your camera. Once you grant access, the application will start streaming video from your camera. Whenever a barcode or QR code is detected in the video stream, the decoded value will be displayed in a list below the video.

## Technologies Used

This application is built using HTML, CSS, and JavaScript. It utilizes the Barcode Detection API, which is available in some modern browsers.

The application is styled using the Foundation CSS framework, which is included via a CDN link.

## Disclaimer

This application was developed as a simple proof-of-concept and may not be suitable for production use. It has been tested in Google Chrome on Android only. The Barcode Detection API is an experimental technology and may not be supported by all browsers or may have limitations in its functionality.

## Author

This application was developed by [Shahriar Malik](https://github.com/ShahriarMalik).
