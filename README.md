# EPC Document Text Extraction using OCR

This project extracts text data from scanned Energy Performance Certificate (EPC) images using Python's Tesseract OCR engine and saves the output into a CSV file.

## Project Details
- Read EPC document images.
- Extract text using Tesseract OCR.
- Save extracted text into a structured CSV file.

## Technologies and Libraries Used
- Python
- Pillow (PIL)
- pytesseract
- pandas

## How to Run
1. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
2. Place your EPC image file (e.g., `38.jpg`) in the working directory.
3. Update the `image_path` variable if necessary in the code.
4. Run the Python script or Jupyter Notebook to extract text and save it into `extracted_text.csv`.

## Project Goal
Automate the extraction of textual data from scanned energy certificates to enable efficient data handling and analysis.
