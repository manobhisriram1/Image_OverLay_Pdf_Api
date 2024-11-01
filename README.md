# ImageOverlayPDF

A Flask-based API for processing images and generating PDFs with overlay text. This project allows users to upload a PNG or JPEG image, overlay the image name on the bottom, and optionally convert the image to a PDF format.

## Features

- **Image Input Handling**: Upload and process a single PNG or JPEG image.
- **Overlaying Image Name**: Overlay the name of the image at the bottom of the uploaded image.
- **PDF Conversion**: Convert the modified image into a PDF if the optional parameter `generate_pdf=true` is included in the request.
- **JSON Response**: The API returns a structured JSON response including:
  - A link to the modified image.
  - A success message.
  - (Optional) A link to the generated PDF.
- **REST API Testing**: Easily test the API using tools like Postman or RESTlet Client.

## Requirements

- Python 3.x
- Flask
- OpenCV
- Pillow
- FPDF
- Pyngrok

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ImageOverlayPDFService.git
