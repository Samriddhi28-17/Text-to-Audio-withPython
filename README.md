# Text-to-Audio-withPython

This is a Google Colab notebook that provides a simple and effective way to convert a PDF document into an audio file. It allows for highly customised conversions, including the ability to select specific pages or a range of pages to turn into audio.

The project is built using Python and leverages powerful open-source libraries for PDF text extraction and text-to-speech conversion.

Note: There may be issues with larger files; separate them, as the Colab file may show a runtime error while processing large files over 400/500 pages

## Features
- Upload a PDF: Easily upload a PDF file directly from your local machine.
- Custom Page Selection: Choose to convert the entire book or specify a custom range of pages (e.g., 1, 3-5, 8).
- High-Quality Audio: The conversion uses Google's Text-to-Speech (gTTS) engine, providing clear and natural-sounding audio.
- Downloadable Output: The final audio file is saved as an MP3 and can be downloaded immediately.

## Getting Started
To use this converter, just open the notebook in Google Colab. The notebook is fully interactive and requires no local setup.

## How it Works
The notebook's code is divided into three main parts:
- Environment Setup: Installs the necessary Python libraries (PyMuPDF and gTTS).
- Core Functionality: Defines the Python functions for extracting text from a PDF and converting that text to an audio file.
- Interactive UI: Uses Google Colab's #@param feature to create a simple user-friendly interface for file uploads and options.

Contributing
If you'd like to contribute, feel free to fork the repository and submit a pull request with your improvements.
