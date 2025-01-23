This Jupyter Notebook (.ipynb) implementation designed to perform Optical Character Recognition (OCR) specifically for extracting text from newspaper images. The notebook processes input images, applies pre-processing techniques, and extracts text using OCR tools.

Features
Image Preprocessing: Enhances newspaper images for better OCR results (e.g., noise removal, binarization).

OCR Integration: Utilizes OCR libraries like Tesseract to extract text from images.

Text Cleaning: Post-processes extracted text to remove unnecessary characters and improve readability.

Batch Processing: Handles multiple newspaper images in a single run.


Example Workflow
Add an image (newspaper.jpg) to the data/ directory.

Execute the notebook.

Extracted text will be saved as newspaper_output.txt in the output/ directory.

Dependencies
Python 3.x

OpenCV

Tesseract OCR

pytesseract

numpy
