# 🚗 APSIT Smart Park

A smart parking management mobile application built using **Flutter** and **Firebase** to streamline parking operations within the APSIT campus.

---

## 📱 Overview

APSIT Smart Park is designed to simplify and optimize parking for students and staff by providing **real-time slot availability**, **quick reservations**, and **smart alerts**.

---

## ✨ Features

- 🔐 **Secure Login**
  - Login using APSIT Moodle ID for authorized access

- 🗺️ **Interactive Parking Map**
  - View parking layout with real-time slot availability

- 🅿️ **Slot Reservation**
  - Reserve parking slots instantly based on vehicle type

- 🔔 **Parking Alerts**
  - Notifications for wrong or restricted parking

- 🧭 **Zone Segregation**
  - Separate parking areas for students and faculty

---

## 🎯 Objectives

- Provide real-time parking availability  
- Reduce time spent searching for parking  
- Enable quick and easy slot reservation  
- Improve parking discipline on campus  
- Ensure efficient space utilization  
- Minimize congestion and unorganized parking  
- Enhance user convenience through a mobile app  

---

## 🛠️ Tech Stack

### Front-End
- **Flutter (Dart)** – Cross-platform mobile development  
- **Material Design 3** – Modern UI components  
- **Provider** – State management  
- **Google Fonts (Poppins)** – UI styling  

### Back-End
- **Firebase Authentication** – Secure login  
- **Cloud Firestore** – NoSQL database  
- **Firebase Realtime Database** – Live updates  
- **Firebase Cloud Messaging (FCM)** – Push notifications  

---

## 📋 Platform Requirements

- Android / iOS smartphone  
- Active internet connection  

---

## 🚀 Getting Started

### Prerequisites
- Flutter SDK installed  
- Firebase project setup  
- Android Studio / VS Code  

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/apsit_smart_park.git

# Navigate to project folder
cd apsit_smart_park

# Install dependencies
flutter pub get

# Run the app
flutter run

📂 Project Structure
lib/
 ├── models/
 ├── services/
 ├── providers/
 ├── screens/
 ├── widgets/
 └── main.dart

 🔒 Security
Authentication via Firebase
Database rules enforced for authorized access
Role-based parking access (Student/Faculty)

