# Image–Text–Speech Converter 🖼️📝🔊

The **Image–Text–Speech Converter** is a Python-based desktop application that allows users to:
- Extract text from images using **OCR**
- Convert extracted or typed text into **speech (audio files)**
- Interact through a **graphical user interface (GUI)** built with Tkinter

This project demonstrates practical use of **Computer Vision, OCR, Text-to-Speech, and GUI development**.

---

##  Features

-  **Image to Text (OCR)**  
  Extracts readable text from image files using Tesseract OCR.

-  **Image to Speech**  
  Converts text extracted from images into an audio file (.mp3).

-  **Text to Speech**  
  Converts user-entered text into speech.

-  **Copy to Clipboard**  
  Extracted text is automatically copied to the clipboard.

-  **Save Audio Files**  
  Speech output can be saved as an MP3 file.

-  **User-Friendly GUI**  
  Built using Tkinter with buttons and dialogs.

---

##  Technologies & Libraries Used

- Python 3
- Tkinter (GUI)
- pytesseract (OCR)
- Tesseract OCR Engine
- gTTS (Google Text-to-Speech)
- Pillow (Image Processing)
- playsound
- pyperclip

---

##  System Requirements

- Python 3.x
- Internet connection (required for gTTS)
- Tesseract OCR installed

---

##  Installation & Setup

### 1️ Install Required Python Packages

*```bash
pip install pillow pytesseract gtts playsound pyperclip
Install Tesseract OCR

*Download from:
https://github.com/tesseract-ocr/tesseract

*Update the Tesseract path in the code:

*pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"

2.**How to Run the Application**

*Clone the repository: git clone https://github.com/Damu987/image-text-speech-converter.git
*Navigate to the project folder and run:python main.py
*Use the GUI buttons to:
   *Convert image → text
   *Convert image → audio
   *Convert text → audio

 ## Key Concepts Demonstrated

 * Optical Character Recognition (OCR)
 * Text-to-Speech synthesis
 * GUI application development
 * File handling
 * Clipboard operations
 * Image processing
 * Error handling

## Project Structure
image-text-speech-converter/
│
├── converter.py
├── _bg_.jpg
├── README.md

 ## Screenshots

<img width="400" height="400" alt="Screenshot 2025-04-20 192126" src="https://github.com/user-attachments/assets/c8a157bd-d1d8-4383-a6cc-8c33ec85698f" />


##  Future Enhancements

 * Offline text-to-speech support
 * Multi-language OCR and speech
 * Voice selection and speed control
 * Improve OCR accuracy with image preprocessing
 * Cross-platform installer

## Author

Damini S
AI & Frontend Enthusiast | Python Developer

GitHub: https://github.com/Damu987

 ## License
This project is licensed under the MIT License.
