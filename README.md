# 📱 IntelliRepair

**IntelliRepair** is a feature-complete native Android application designed to assist users with device management, repair tracking, and guided troubleshooting. 

*Note: This repository serves as a portfolio showcase. The source code is kept private to protect proprietary API keys and backend infrastructure.*

## ✨ Key Features
* **AI Repair Assistant:** Interactive chatbot powered by an LLM (via OpenRouter API) to help diagnose hardware issues.
* **Step-by-Step Guides:** Direct integration with the **iFixit API** to search, view, and save professional repair manuals.
* **Device Inventory:** Manage owned devices and log ongoing or completed repairs.
* **Saved Favorites:** Bookmark frequently used repair guides for offline-ready viewing.
* **Secure Authentication:** User login and profile synchronization using Firebase Authentication.

## 🛠 Technical Architecture
The application follows modern Android development principles with a modular architecture:
* **Language:** Java 11
* **Minimum SDK:** Android 7.0 (API 24) / Target SDK: 36
* **Local Persistence:** Room Database (SQLite) with reactive LiveData observers.
* **Networking:** Retrofit2 & OkHttp for REST API calls (iFixit & OpenRouter).
* **Image Caching:** Glide
* **UI/UX:** Material Design 3 components and ViewBinding.

## 📸 Screenshots
*(Add screenshots of your app here by dragging and dropping images directly into GitHub's editor)*
