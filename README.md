# Academic_projects

# Automatic Number Plate Recognition System

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/Python-3.8+-brightgreen.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-blue.svg)

## 📖 Overview

The **Automatic Number Plate Recognition (ANPR) System** is a computer vision-based application designed to detect and recognize license plates from vehicle images or video streams. This project leverages image processing techniques, machine learning, and Optical Character Recognition (OCR) to accurately identify and extract license plate information.

## 🚀 Features

- **Real-time License Plate Detection:** Detects and recognizes license plates from live video streams or pre-recorded footage.
- **High Accuracy OCR:** Utilizes Tesseract OCR to convert license plate images into readable text.
- **Multi-Plate Recognition:** Capable of recognizing multiple plates in a single frame.
- **Image Processing Techniques:** Includes edge detection, image filtering, and contour detection for accurate plate localization.
- **User-Friendly Interface:** Simple command-line or graphical user interface for ease of use.

## 🛠️ Technologies Used

- **Programming Language:** Python 3.8+
- **Libraries:** 
  - OpenCV (for image processing and video stream handling)
  - Tesseract OCR (for text recognition)
  - NumPy (for numerical operations)
  - Matplotlib (for visualization)
- **Other Tools:**
  - Pre-trained Haar Cascade Classifier for license plate detection
  - Custom-trained models for improved accuracy (optional)

## 📂 Project Structure

```
├── data/                         # Sample images and videos
├── models/                       # Pre-trained and custom models
├── src/                          # Source code
│   ├── detect_plate.py           # License plate detection script
│   ├── recognize_plate.py        # OCR and recognition script
│   ├── utils.py                  # Utility functions
├── README.md                     # Project README
└── requirements.txt              # Python dependencies
```

## ⚙️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/lovely-PRAKASH/Academic_project/Automatic Number Plate Recognition System.git
   cd ANPR-System
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Install Tesseract OCR:**
   - Follow the instructions [here](https://github.com/tesseract-ocr/tesseract) to install Tesseract on your system.

## 🚦 Usage

1. **Detect and recognize license plates from an image:**
   ```bash
   python src/detect_plate.py --image path/to/your/image.jpg
   ```

2. **Process a video stream:**
   ```bash
   python src/recognize_plate.py --video path/to/your/video.mp4
   ```

3. **Customize parameters:**
   - Modify detection and OCR parameters in the `config.json` file.

## 🧪 Testing

- Use the provided sample images and videos in the `data/` directory to test the system.
- Modify or add your own test cases for further validation.

## 🌟 Contributing

Contributions are welcome! Please fork this repository and submit a pull request for any enhancements, bug fixes, or additional features.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

For any queries, please reach out via [email@example.com](mailto:prakash.arthanari2002@gmail.com).

---

