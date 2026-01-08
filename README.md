## Image Text Extraction using Tesseract OCR

A simple Python project that extracts text from images using **Tesseract OCR** and **Pillow**.

---

### About the Project
This project demonstrates how Optical Character Recognition (OCR) can be used to read and extract text from image files.  
It is useful for automating text extraction from labels, documents, and scanned images.

---

### Features
- Extracts text from image files  
- Uses Tesseract OCR engine  
- Simple and lightweight Python script  
- Easy to extend for file saving or batch processing  

---

### Technologies Used
- Python  
- Tesseract OCR  
- Pillow (PIL)  

---

### Project Structure

label-reading-ocr/
│
├── main.py
├── sample_datasets/
│ └── test3.jpg
└── README.md


---

## How It Works
1. Loads an image using Pillow  
2. Passes the image to Tesseract OCR  
3. Extracts text from the image  
4. Prints the extracted text to the console  

---

### Installation & Setup

#### 1. Install Tesseract OCR
- Download and install from:  
  https://github.com/tesseract-ocr/tesseract  
- Note the installation path (used in code)

#### 2. Install Python Dependencies
    ```bash
    pip install pytesseract pillow

#### 3. Configure Tesseract Path (Windows)
     ```bash
     pytesseract.pytesseract.tesseract_cmd = r"C:\Program Files\Tesseract-OCR\tesseract.exe"

---

### Run the Project
    ```bash
    python main.py

---

### Sample Output
    ```bash
    Extracted text from image will be displayed here

---

### 📈 Applications
- Label reading systems  
- Document digitization  
- Automated data entry  
- OCR-based AI projects  

---

### 🔮 Future Improvements
- Save extracted text to a file  
- Support multiple images  
- Add GUI or web interface  
- Improve accuracy with image preprocessing  

---

### License
This project is intended for educational purposes.

