# Image Background Remover

## Overview

This application allows users to remove the background from their images using the `rembg` library. The app provides an easy-to-use interface where users can upload an image, view the original and processed images side by side, and download the background-removed image.

## Features

- **Image Upload**: Upload images in PNG, JPG, or JPEG formats.
- **Background Removal**: Removes the background from the uploaded image using the `rembg` library.
- **Image Preview**: Displays the original and background-removed images side by side.
- **Download Processed Image**: Download the processed image from the sidebar.

## Installation

To run this application, you need to have Python installed on your system along with the following libraries:

- `streamlit`
- `rembg`
- `Pillow`

You can install the required libraries using the following command:

```bash
pip install streamlit rembg Pillow
