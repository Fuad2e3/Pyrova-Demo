<div align="center">

# 💪 Pyrova
### The Ultimate AI-Powered Fitness & Wellness Ecosystem

[![Platform](https://img.shields.io/badge/Platform-Flutter-blue?style=for-the-badge&logo=flutter)](https://flutter.dev/)
[![Language](https://img.shields.io/badge/Language-Dart-0175C2?style=for-the-badge&logo=dart)](https://dart.dev/)
[![Backend](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs)](https://nodejs.org/)
[![API](https://img.shields.io/badge/API-Express.js-000000?style=for-the-badge&logo=express)](https://expressjs.com/)
[![Database](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql)](https://www.mysql.com/)
[![AI](https://img.shields.io/badge/AI-Gemini-blueviolet?style=for-the-badge&logo=google-gemini)](https://deepmind.google/technologies/gemini/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Empowering users with AI-powered fitness coaching, personalized workout plans, nutrition tracking, and real-time health insights.**

---

</div>

## 🌟 Overview

**Pyrova** is a next-generation fitness and wellness platform designed to help users achieve their health goals through intelligent workout planning, nutrition management, and AI-driven guidance. Developed by **Team Softece**, the application delivers a complete ecosystem for fitness enthusiasts, beginners, and athletes.

## 🚀 Key Features

-   🤖 **AI Fitness Coach**: Personalized workout recommendations powered by Gemini AI.
-   🏋️ **Custom Workout Plans**: Goal-based training programs tailored to user preferences.
-   🍎 **Nutrition Tracking**: Monitor meals, calories, macros, and daily nutrition.
-   📈 **Progress Analytics**: Track weight, BMI, workout performance, and fitness milestones.
-   🔥 **Exercise Library**: Access detailed exercise guides and workout demonstrations.
-   💧 **Water Intake Monitoring**: Stay hydrated with smart reminders.
-   🎯 **Goal Setting System**: Create and monitor personal fitness goals.
-   ⏰ **Workout Reminders**: Never miss a workout session.
-   🏆 **Achievements & Challenges**: Earn badges and stay motivated.
-   👥 **Community Engagement**: Connect and compete with other fitness enthusiasts.

## 🛠️ Tech Stack

-   **Frontend**: Flutter (Dart)
-   **Backend**: Node.js, Express.js
-   **Database**: MySQL
-   **REST API**: Custom-built for seamless client-server communication
-   **AI Engine**: Google Gemini API
-   **Authentication**: Firebase Authentication
-   **Architecture**: MVC (Model-View-Controller) / MVVM

## 📁 Project Structure

```text
Pyrova/
├── client/                      # Flutter Application
│   ├── lib/                     # Dart source code
│   │   ├── models/
│   │   ├── screens/
│   │   ├── services/            # API communication
│   │   └── widgets/
│   ├── assets/                  # Images, fonts, animations
│   └── pubspec.yaml
├── server/                      # Node.js Express Backend
│   ├── config/                  # Database configuration
│   ├── controllers/             # Business logic
│   ├── models/                  # MySQL models
│   ├── routes/                  # API endpoints
│   ├── index.js                 # Entry point
│   └── package.json
└── LICENSE                      # MIT License
```

## ⚙️ Installation

### Backend Setup (Node.js)
1.  **Navigate to server directory**:
    ```bash
    cd server
    ```
2.  **Install dependencies**:
    ```bash
    npm install
    ```
3.  **Configure Environment Variables**:
    - Create a `.env` file and add your MySQL and Gemini API credentials.
4.  **Run the server**:
    ```bash
    npm start
    ```

### Frontend Setup (Flutter)
1.  **Navigate to client directory**:
    ```bash
    cd client
    ```
2.  **Install packages**:
    ```bash
    flutter pub get
    ```
3.  **Run the app**:
    ```bash
    flutter run
    ```

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

<p align="center">
  Developed with ❤️ by <b>Team Softece</b><br>
  <i>Pyrova</i>
</p>
