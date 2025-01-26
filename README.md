# Auto Table Extractor and Data Entry Bot

This project is an automation script that performs the following tasks:
1. Extracts tabular data from an image using OCR (Optical Character Recognition).
2. Opens Google Chrome to access Google Sheets (or any other application).
3. Automatically inputs the extracted data into Google Sheets.

## Features
- **Image Click Automation**: Uses template matching to locate and click on specific elements in the screen.
- **OCR with Tesseract**: Extracts table data from images and formats it into a structured array.
- **Google Sheets Automation**: Automates data entry using `pyautogui` to simulate keyboard actions.

## Requirements
- Python 3.x
- Tesseract-OCR
- The following Python libraries:
  - `pyautogui`
  - `mss`
  - `opencv-python`
  - `numpy`
  - `pytesseract`


## Tesseract OCR

You need to install Tesseract OCR for text recognition. You can download it from the following link: https://github.com/tesseract-ocr/tesseract/releases/tag/5.5.0
