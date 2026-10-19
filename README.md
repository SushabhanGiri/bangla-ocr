# Bangla OCR — Sushabhan Giri

![App Screenshot](./screenshot.jpg)

An Optical Character Recognition (OCR) application for Bangla image to text conversion.

**Fork maintained by [Sushabhan Giri](https://github.com/SushabhanGiri).**

## Features

- 📖 Accurate Bangla text extraction from images/PDFs
- ✍️ BERT-based text correction
- 🖼️ Supports PNG, JPG, PDF formats

## Installation

### Windows Executable
1. Check the [original project’s releases](https://github.com/habibahsan/bangla-ocr/releases) for a Windows executable, if available. Release binaries are not copied automatically to this fork.
2. Run `BanglaOCR.exe`

### From Source
```bash
# Clone repository
git clone https://github.com/SushabhanGiri/bangla-ocr.git
cd bangla-ocr

# Install dependencies
pip install -r requirements.txt

# Run application
python main.py
```

## Usage
1. Click "Open Image" to select a file
2. Export results and save as text or word file

## Building from Source
```bash
# Install PyInstaller
pip install pyinstaller

# Build executable
python build.py
```

## Requirements
- Python 3.12
- Tesseract OCR 5.x [Official Installer](https://github.com/UB-Mannheim/tesseract/wiki)
- 4GB+ RAM (8GB recommended for BERT model)

## Attribution

This repository is a fork of [habibahsan/bangla-ocr](https://github.com/habibahsan/bangla-ocr), originally developed by **Md Ahsan Habib** ([@habibahsan](https://github.com/habibahsan)) and the upstream contributors.

The original source code, commit history, copyright notice, and MIT license are preserved. Changes in this fork are currently limited to attribution and repository-specific documentation.

## License
MIT © 2025 Bangla OCR. See [LICENSE](LICENSE) for the original copyright and permission notice. Third-party components retain their respective licenses.
