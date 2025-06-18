<h1 align="center">Hi 👋, I'm yashvinthan</h1>
<h3 align="center">A passionate developer from India</h3>

- 🔭 I’m currently working on **AI Camera with ESP32Cam & GPT-4o**
# 📸 AI Vision Assistant with ESP32-CAM, OLED, and GPT-4o

This project combines embedded AI with cloud intelligence. It uses an ESP32-CAM module to capture an image, encodes it in Base64, and sends it to OpenAI's GPT-4o API for visual analysis. The result is displayed on an OLED screen and supported with buzzer feedback.

---

## 🔧 Hardware Used
- ESP32-CAM AI Thinker Module  
- 0.96" OLED Display (SSD1306, I2C)  
- Buzzer  
- Push button  
- Optional: Battery pack or USB power

---

## 🧠 Features
- Image capture triggered by button press  
- Image encoded in Base64 and sent via Wi-Fi to GPT-4o API  
- GPT-4o responds with natural language description of the image  
- Result displayed on OLED with scrollable output  
- Buzzer feedback on capture events  
- Built-in text wrapping & vertical centering for clean OLED rendering

---

## 📦 Libraries Required
- `WiFi.h`  
- `HTTPClient.h`  
- `esp_camera.h`  
- `Base64.h`  
- `Adafruit_SSD1306`  
- `Adafruit_GFX`  
- `ArduinoJson`  
- `Wire.h`

Tested on:
- Arduino IDE 2.3.2  
- ESP32 Board v3.0.0  
- OLED Library v2.5.13  
- ArduinoJson v7.1.0  

---

## 🖼️ Flow

```
[Capture Image] → [Base64 Encoding] → [Send to GPT-4o] → 
[Receive Analysis] → [Display on OLED] + [Beep]
```

---

## 💻 Setup

1. Install libraries listed above
2. Replace your Wi-Fi credentials and API Key in the sketch:
```cpp
const char* ssid = "your_SSID";
const char* password = "your_PASSWORD";
const String apiKey = "your_OPENAI_API_KEY";
```
3. Upload to your ESP32-CAM via Arduino IDE  
4. Connect OLED to GPIO 14 (SCL) and GPIO 15 (SDA)  
5. Press the button to trigger image capture and analysis

---

## 🎯 Use Cases

- Low-cost AI vision assistant for education  
- Smart kiosk visual assistant  
- STEM demonstrations with OpenAI  
- Accessible tool for visually impaired (OLED + Audio cues)

---

## 📃 License
MIT License – Feel free to use and modify

---

## 🙌 Credits
Created by Yashvinthan M.

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/> </a> </p>
