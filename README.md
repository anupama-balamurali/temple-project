# Tempvia - Temple management App
# 🔐 Temple Management App - Authentication Module

A Flutter-based authentication system for the Temple Management App integrated with Firebase. This module provides secure user authentication with Login and Sign Up screens and supports multiple platforms using FlutterFire.

---

## 📌 Features

- 🔑 User Login Screen
- 📝 User Registration Screen
- 🔥 Firebase Initialization
- 🌐 Cross-platform Support
  - Android
  - iOS
  - Web
  - Windows
  - macOS
- 📱 Clean and Responsive UI
- 🎨 Material Design Interface
- 🔄 Navigation between Login and Sign Up

---

## 📂 Project Structure

```
lib/
│── main.dart
│── signup.dart
│── firebase_options.dart
```

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Flutter | Frontend Development |
| Firebase | Backend Services |
| Firebase Authentication | User Authentication |
| Dart | Programming Language |
| Material UI | User Interface |

---

## 📄 File Description

### 📌 firebase_options.dart

This file is generated automatically using the FlutterFire CLI.

Responsibilities:

- Stores Firebase configuration
- Initializes Firebase for each platform
- Supports Android, iOS, Web, Windows and macOS

---

### 📌 main.dart

Main entry point of the application.

Responsibilities:

- Initializes Firebase
- Starts the application
- Defines routes
- Displays Login Screen
- Navigates to Sign Up Screen

Routes Used

```dart
'/'
'/signup'
```

---

### 📌 signup.dart

Handles user registration interface.

Features

- Name Field
- Email Field
- Password Field
- Confirm Password Field
- Terms & Conditions Checkbox
- Sign Up Button
- Navigate back to Login

---

## 📱 Screens

### Login Screen

- Username
- Password
- Login Button
- Register Here Navigation

---

### Sign Up Screen

- Name
- Email
- Password
- Confirm Password
- Terms & Conditions
- Sign Up Button
- Sign In Navigation

---

## 🚀 Getting Started

### 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/temple-management-app.git
```

---

### 2️⃣ Install Packages

```bash
flutter pub get
```

---

### 3️⃣ Configure Firebase

Install FlutterFire CLI

```bash
dart pub global activate flutterfire_cli
```

Configure Firebase

```bash
flutterfire configure
```

---

### 4️⃣ Run the Project

```bash
flutter run
```

---

## 📦 Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter

  firebase_core: latest
```

If authentication is implemented:

```yaml
firebase_auth: latest
```

---

## 🎨 UI Components

- TextField
- ElevatedButton
- Checkbox
- GestureDetector
- MaterialApp
- Scaffold
- Column
- Row
- Padding

---

## 🔄 Navigation Flow

```
App Start
     │
     ▼
Login Screen
     │
Register Here
     ▼
Sign Up Screen
     │
Sign In
     ▼
Login Screen
```

---

## 🔥 Firebase Platforms Supported

✅ Android

✅ iOS

✅ Web

✅ Windows

✅ macOS

---

## 📌 Future Improvements

- Firebase Authentication
- Email Verification
- Forgot Password
- Google Sign-In
- Phone Authentication
- User Profile
- Remember Me
- Input Validation
- Password Strength Indicator
- Dark Mode
- Form Validation
- Loading Indicators
---

## 📄 License

This project is developed for company and academic purposes.

---

⭐ If you found this project useful, don't forget to star the repository!
