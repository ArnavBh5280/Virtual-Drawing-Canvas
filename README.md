# 🖐️ Virtual Canvas - AI Powered Air Drawing System ✨

([images/banner.png](https://github.com/ArnavBh5280/Virtual-Drawing-Canvas/blob/38b65c6460559825d6b84c8f25bebc9b14b01483/ai_output1.png))

## 🧠 Project Overview

**Virtual Canvas** is a web-based, AI-powered air drawing system that allows users to draw, paint, and solve mathematical problems using only hand gestures — no mouse, stylus, or touchscreen required.

It blends **Computer Vision**, **MediaPipe Hand Tracking**, and **Generative AI (Gemini)** to create an intuitive and accessible hands-free interface for real-time digital creativity and problem-solving.

---

## 🎯 Key Features

✅ **Real-time Hand Tracking** using MediaPipe  
✅ **Virtual Drawing Canvas** controlled via finger gestures  
✅ **Math Problem Recognition & Solving** with Gemini AI  
✅ **Gesture-based Tool Switching** (e.g., draw, erase, color)  
✅ **Touchless and Accessible Interface**  
✅ **Web-based (Flask Backend + HTML/JS Frontend)**  
✅ **AI Output Displayed Live**

---

## 🖼️ Demo Screenshots

| Virtual Drawing Interface | AI Output Example |
|---------------------------|-------------------|
| ![Drawing](images/drawing.png) | ![AI Output](images/ai_output1.png) |
| ![AI Output 2](images/ai_output2.png) | ![AI Output 3](images/ai_output3.png) |

> 💡 Replace `/images/...` with your actual image paths in the repo.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python (Flask)  
- **Computer Vision**: OpenCV, MediaPipe, cvzone  
- **AI Integration**: Gemini (Generative AI API)  
- **Asynchronous Processing**: Python threading  
- **Image Handling**: PIL, NumPy


---

## 🧪 Gesture Controls

| Gesture                        | Action                      |
|-------------------------------|-----------------------------|
| ✋ All fingers up              | Send drawing to AI          |
| ☝️ Only index finger up       | Draw                        |
| 👍 Only thumb up              | Erase/clear canvas          |
| ✌️ Index + Middle finger up   | Move cursor (no drawing)    |

---

## 🎓 Applications

- 🎒 **Remote Learning & Education**: Smart teaching aid for live math solving and drawing  
- 🖼️ **Digital Art Creation**: Touchless sketching for artists  
- 🩺 **Healthcare Interfaces**: Hygienic, gesture-based input in hospitals  
- 👨‍🦽 **Assistive Tech**: Hands-free computing for differently-abled users  
- 🕹️ **AR/VR & Gaming**: Hand-controlled interaction platforms  
- 💡 **Tech Fests & Exhibitions**: Live demo of AI + CV-powered gesture UI

---

## 🚧 Limitations

- 📷 **Lighting Dependent**: Poor lighting may affect gesture accuracy  
- 🖐️ **Limited Gestures**: Only a small set of gestures are mapped  
- 🔢 **Math-Centric AI**: AI works best for numeric/math-based drawings  
- 🕒 **Slight Delay**: AI responses take a few seconds depending on internet speed

---

## 🌱 Future Enhancements

- 🔠 **OCR Integration** for better handwritten character recognition  
- 🔊 **Voice Feedback** to assist visually impaired users  
- ☁️ **Cloud Save & Sync** to store drawings and AI outputs  
- ✋ **Custom Gesture Mapping** (user-defined shortcuts)  
- 📱 **Mobile App Support** via Flutter or React Native  
- 🌍 **Multi-Language AI Explanations**

---

## 🚀 How to Run Locally

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/virtual-canvas.git
   cd virtual-canvas


2. **Install Required Packages**
   ```bash
   pip install -r requirements.txt

3. **Run the Application**
   ```bash
   python app.py

---

## 📄 License

This project is for academic and demonstration purposes only.  
For commercial use, please contact the authors.

