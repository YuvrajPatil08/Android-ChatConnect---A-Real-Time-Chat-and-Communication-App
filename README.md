# 💬 Chatoon – Real-Time Chat Application with Firebase & Jetpack Compose

---

## 📌 Project Description

Chatoon is a modern, real-time chat application designed for Android using Jetpack Compose and Firebase services. The app allows users to register and authenticate securely via Firebase Authentication, ensuring smooth and reliable access. Once logged in, users can create and join chat rooms, enabling one-on-one or group conversations with real-time updates powered by Cloud Firestore.

Messages are delivered instantly and efficiently through Firebase Cloud Messaging (FCM), providing a responsive and interactive user experience. With Jetpack Compose, the UI is fully declarative, offering a sleek, intuitive, and adaptive design across different devices. The application ensures data synchronization, secure communication, and a scalable architecture, making it suitable for dynamic chat interactions in real-time.

---


## 🛠 Technologies Used

- *Kotlin* (Android)
- *Jetpack Compose* (UI)
- *Firebase Authentication* (User Management)
- *Firebase Firestore* (Real-Time Database)
- *Firebase Cloud Messaging* (Push Notifications)
- *Material 3* (UI Components)

---

## ⚙ Installation & Setup

### Prerequisites

- Android Studio (Flamingo or newer)
- Firebase Project (with Authentication, Firestore, and Cloud Messaging enabled)

### Steps

1. *Clone the repository:*
    bash
    git clone https://github.com/Digu45/Android-chatconnect-real-time-chat-app-main.git
    cd Chatoon/app
    

2. *Add your Firebase config:*
    - Download google-services.json from your Firebase Console and place it in app/.

3. *Build the project:*
    - Open in Android Studio and sync Gradle.

4. *Run the app:*
    - Connect an Android device or use an emulator.
    - Click *Run*.

---

## 🚀 Features

- User Registration & Login (with validation)
- Create and join chat rooms
- Real-time messaging with sender display
- Push notifications for new messages
- Responsive Material 3 UI
- Password strength & confirmation checks

---

## 🔒 Security & Best Practices

- Passwords are validated for strength and confirmed before registration.
- User data is stored securely in Firestore.
- Push notifications use FCM topics per chat room.

---

## 📝 How to Use

1. *Register* a new account or *log in*.
2. *Create* a chat room or *join* an existing one.
3. *Send messages* in real time and receive notifications.

---

---

## 🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## Contact

For questions or support, please contact [diguvapilkar45@gmail.com](mailto:diguvapilkar45@gmail.com).