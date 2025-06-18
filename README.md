<h1 align="center">Hi 👋, I'm yashvinthan</h1>
<h3 align="center">A passionate developer from India</h3>

- 🔭 I’m currently working on **AI Camera with ESP32Cam & GPT-4o**
# 📸 AI Camera with ESP32-CAM & GPT-4o

An AI-powered camera system using ESP32-CAM that captures images and sends them to a backend integrated with OpenAI’s GPT-4o Vision API for real-time image analysis and human-like responses.

## 🚀 Features

- 🖼️ Image capture via ESP32-CAM (triggered by button or motion)
- 🌐 Wi-Fi-enabled HTTP image transfer to backend server
- 🧠 GPT-4o Vision API integration for smart image interpretation
- 🔊 Optional voice response using text-to-speech
- 📱 Optional Telegram bot/web dashboard integration

---

## 🔧 Tech Stack

- **Hardware**: ESP32-CAM, MicroSD module (optional), power supply
- **Firmware**: Arduino IDE + ESP32 HTTPClient
- **Backend**: Python (Flask) or Node.js (Express)
- **AI**: OpenAI GPT-4o Vision API
- **Extras**: pyttsx3 / gTTS (for TTS), Blynk/Telegram for alerts

---

## 📸 How It Works

1. ESP32-CAM captures an image (manually or via motion).
2. Sends image to a Flask backend via HTTP POST.
3. Backend sends image to GPT-4o Vision API.
4. GPT-4o returns a descriptive or contextual response.
5. System outputs response as:
   - Text (console/web)
   - Audio (TTS)
   - Chat message (optional bot)

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> </p>
