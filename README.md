<div align="center">

# 💪 Pyrova
### **The Ultimate AI-Powered Fitness & Wellness Ecosystem**

[![Platform](https://img.shields.io/badge/Platform-Flutter-blue?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev/)
[![Language](https://img.shields.io/badge/Language-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)](https://dart.dev/)
[![Backend](https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![API](https://img.shields.io/badge/API-Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Database](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![AI](https://img.shields.io/badge/AI-Gemini-8E75FF?style=for-the-badge&logo=google-gemini&logoColor=white)](https://deepmind.google/technologies/gemini/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**Empowering users with AI-powered fitness coaching, personalized workout plans, nutrition tracking, and real-time health insights.**

---

[Explore Features](#-key-features) • [Visual Showcase](#-app-screenshot-gallery) • [Project Structure](#-project-structure) • [Tech Stack](#-tech-stack)

</div>

---

## 📖 Overview
**Pyrova** is a next-generation fitness, bodybuilding, and wellness platform designed to assist users in transforming their physical health through personalized workout routines, scientific macro-nutrition tracking, and AI-driven coaching. Engineered with precision by **Softece**, the application delivers a complete, holistic ecosystem for fitness beginners, gym regulars, and competitive athletes alike.

---

## ✨ Key Features

- 🤖 **AI Fitness Coach:** Real-time conversational fitness guidance and form advice powered by Google Gemini AI.
- 🏋️ **Goal-Centric Workout Plans:** Personalized training splits for fat loss, muscle hypertrophy, or endurance.
- 🍎 **Macro & Nutrition Tracking:** Log daily meals, calculate caloric deficits/surpluses, and monitor macronutrient distribution.
- 📈 **Performance Analytics:** Interactive charts tracking weight trends, body measurements, volume load, and PR milestones.
- 🔥 **HD Exercise Library:** Comprehensive directory of exercises with targeted muscle group diagrams and movement guides.
- 💧 **Smart Hydration Tracker:** Adaptive daily water intake targets with timely reminders.
- 🎯 **Milestone & Streak Engine:** Earn motivational achievement badges and sustain daily consistency streaks.
- 👥 **Community & Leaderboards:** Share transformation progress, compare milestones, and encourage fellow athletes.

---

## 🖼️ App Screenshot Gallery

### 🚀 Onboarding & Workout Exploration
*Intuitive discovery of training routines and daily coaching insights.*

<p align="center">
  <img src="photo/1.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 1">
  <img src="photo/2.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 2">
  <img src="photo/3.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 3">
</p>

---

### 🏋️ Active Training & Session Logging
*Real-time rest timers, set trackers, and guided movement execution.*

<p align="center">
  <img src="photo/4.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 4">
  <img src="photo/5.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 5">
  <img src="photo/6.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 6">
</p>

---

### 🍎 Nutrition, Macros & Water Intake
*Precision tracking of daily calories, protein, carbs, and hydration.*

<p align="center">
  <img src="photo/7.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 7">
  <img src="photo/8.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 8">
  <img src="photo/9.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 9">
</p>

---

### 📈 Analytics & Progress Visualizations
*Comprehensive telemetry of weight change, body composition, and performance.*

<p align="center">
  <img src="photo/10.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 10">
  <img src="photo/11.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 11">
  <img src="photo/12.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 12">
</p>

---

### 👤 Profile, Badges & Customization
*Personalized goals, achievement shelves, and app configuration.*

<p align="center">
  <img src="photo/13.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 13">
  <img src="photo/14.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 14">
  <img src="photo/15.jpg" width="180" style="border-radius: 12px; border: 1px solid #ddd; margin: 5px;" alt="Screen 15">
</p>

---

## 📁 Project Structure

```text
Pyrova/
├── client/                      # Flutter Mobile Application
│   ├── lib/                     # Dart source code
│   │   ├── models/              # User, Workout, Nutrition & Analytics models
│   │   ├── screens/             # UI layers (Dashboard, Workouts, Tracker, Profile)
│   │   ├── services/            # REST API communication & Gemini client
│   │   └── widgets/             # Custom charts, timer cards & progress bars
│   ├── assets/                  # Icons, illustrations, and Lottie animations
│   └── pubspec.yaml
├── server/                      # Node.js + Express REST API Backend
│   ├── config/                  # Database connections & environment setup
│   ├── controllers/             # Workout logic, Nutrition calculus & User auth
│   ├── models/                  # MySQL relational schemas
│   ├── routes/                  # API endpoints
│   ├── index.js                 # Server entry point
│   └── package.json
└── README.md
```

---

## 🛠️ Tech Stack

| Layer | Technology |
| :--- | :--- |
| **Mobile App** | Flutter (Dart SDK 3.x) |
| **Backend API** | Node.js + Express.js |
| **Database** | MySQL (User history, workouts, meal logs) |
| **AI Engine** | Google Gemini API (`generativeai`) |
| **State Management** | Provider / Riverpod |
| **Visualization** | `fl_chart` for dynamic progress trends |
| **Authentication** | Firebase Auth & JWT |

---

## ⚙️ Getting Started

### Backend Setup
```bash
cd server
npm install
# Configure MySQL credentials in .env
npm start
```

### Mobile App Setup
```bash
cd client
flutter pub get
flutter run
```

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed with ❤️ by Fuad**  
*Developed by Softece*  
*Pyrova*

</div>
