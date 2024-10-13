# HEIF to JPEG Image Converter

This project provides a simple Python script to upload, convert, and display images in HEIF (High-Efficiency Image File) format, saving them as JPEGs. This script is designed to work in Google Colab and leverages `pillow-heif` and `pyheif` libraries for handling HEIF images.

## Features

- Upload HEIF images directly in Google Colab.
- Convert HEIF images to JPEG format.
- Display the uploaded HEIF image.
- Save the converted image as a JPEG file.

## Prerequisites

Make sure you have the following libraries installed:

```bash
!pip install pyheif
!pip install pillow-heif
```

## How to Use

1. Clone the repository or copy the code into your Colab notebook.
2. Upload a HEIF image when prompted.
3. The script will display the uploaded image and save it as `converted_image.jpg`.

## License

This project is licensed under the MIT License.