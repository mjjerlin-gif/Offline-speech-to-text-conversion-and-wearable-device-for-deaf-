# Speech to text App

This is an Android app that uses **Vosk Offline Speech Recognition** and **Bluetooth** to receive messages from an ESP32 device.  
When the ESP32 sends a "TOUCHED" message, the app starts offline speech recognition and displays the recognized text.

## Features
- Works fully **offline** (Vosk model).
- Connects to ESP32 via **Bluetooth**.
- Displays recognized speech in the app.

## How to Run
1. Clone or download this repository.
2. Extract the `.zip` file if downloaded.
3. Open the project in **Android Studio**.
4. Build and run on an Android device (Android 8+ recommended).

## Requirements
- Android Studio (latest version).
- Vosk library integrated in the app.
- ESP32 device sending `"TOUCHED"` over Bluetooth.

## License
This project is for educational purposes.

