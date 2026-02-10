# 🗣️ Smart Reader for Visually Impaired  
### OCR-Based Text-to-Speech Assistive Device

<p align="center">

![Python](https://img.shields.io/badge/Python-3.9-blue)
![RaspberryPi](https://img.shields.io/badge/Raspberry%20Pi-4-red)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)
![OCR](https://img.shields.io/badge/OCR-Tesseract-orange)
![TTS](https://img.shields.io/badge/TTS-Festival-yellow)
![Embedded](https://img.shields.io/badge/Embedded-Systems-black)
![IEEE](https://img.shields.io/badge/Published-IEEE-success)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

</p>

---

## 👨‍🎓 About the Project

**Smart Reader for Visually Impaired** is a Raspberry Pi–based assistive embedded system that converts printed text into audible speech in real-time using **Optical Character Recognition (OCR)** and **Text-to-Speech (TTS)** technologies.

This project was developed as a **Final Year Major Project** in:

🎓 **Electronics & Communication Engineering (ECE)**  
🏫 **REVA University, Bengaluru**  

📄 Published at **IEEE ICCCNT Conference**

**Author:** **Kuragayala Sree Harsha**

---

## 📸 Project Images

### Device
![Device](docs/device.jpg)

### Hardware Architecture
![Hardware](docs/hardware_architecture.png)

### Process Flow
![Flow](docs/flow.png)

### OCR Output
![OCR](docs/ocr_result.png)

---

## 🎯 Objective

- Enable visually impaired users to read printed text independently  
- Convert **Image → Text → Speech** in real time  
- Simple one-button interface  
- High accuracy and fast processing  

---

## 🏗️ System Architecture

### Hardware Components

- Raspberry Pi 4 Model B  
- Logitech C270 HD Webcam  
- Metal LED Push Button (GPIO17)  
- Bluetooth Speaker  
- 5V Power Adapter  

### Software Stack

| Component | Technology |
|----------|-----------|
| Programming | Python |
| Image Processing | OpenCV |
| OCR | Pytesseract |
| Text-to-Speech | Festival |
| Hardware Control | RPi.GPIO |
| OS | Raspberry Pi OS |

---

## ⚙️ Working Principle

1. User presses push button  
2. Camera captures printed text image  
3. Image preprocessing using OpenCV  
4. OCR extracts text using Tesseract  
5. Text converted to speech using Festival  
6. Audio output via Bluetooth speaker  

---

## 📊 Performance

| Metric | Result |
|-------|--------|
| Average Accuracy | **97.13%** |
| Processing Time | **~1.1 sec/image** |
| Output | Audio + Text |

---

## 👨‍💻 My Contributions

- Designed complete **hardware architecture**
- Built **OCR + Text-to-Speech pipeline**
- Integrated **camera, push button, and speaker with Raspberry Pi**
- Implemented **real-time image capture and preprocessing**
- Optimized OCR for **high accuracy and fast performance**
- Developed full **embedded Python application**
- Conducted **performance testing and evaluation**
- Designed and built **3D device enclosure**
- Co-authored **IEEE research publication**

---

## 🚀 Features

- Real-time OCR reading  
- One-button operation  
- Embedded hardware + software integration  
- Assistive technology for visually impaired  
- Portable and low-cost design  
- High accuracy and fast processing  

---

## ⚠️ Limitations

- Handwritten text recognition limited  
- Small font detection reduced  
- Currently supports English only  

---

## 🔮 Future Improvements

- Deep Learning based OCR  
- Multilingual speech support  
- Handwritten text recognition  
- AI-based text understanding  
- Mobile application integration  
- Smart autofocus camera system  

---

## 📚 IEEE Publication

**Smart Reader / SpeakEasy Reader — OCR-Based Assistive Device**  
Published at **15th IEEE ICCCNT Conference**

📄 Full paper available in: https://ieeexplore.ieee.org/document/10723858

👤 Author

Kuragayala Sree Harsha
B.Tech – Electronics & Communication Engineering
REVA University, Bengaluru
sreeharsha.k83@gmail.com
