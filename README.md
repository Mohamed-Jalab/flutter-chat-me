# Chat Me 💬

A real-time chat application built with **Flutter, Firebase Authentication, Cloud Firestore, and Cubit (flutter_bloc)**.

Chat Me is a learning project designed to demonstrate how Flutter can be used to build a mobile messaging application with Firebase services and state management.

## ✨ Features

- **User Authentication** — Sign in and registration using Firebase Authentication.
- **Real-Time Messaging** — Receive message updates using Cloud Firestore streams.
- **Message Information** — Display message text, sender name, and timestamp data.
- **State Management** — Organize application logic using Cubit and flutter_bloc.
- **Reusable Widgets** — Use custom widgets for buttons, text fields, and messages.
- **Firebase Integration** — Connect the Flutter application to Firebase services.

## 🛠️ Tech Stack

| Technology | Purpose |
| --- | --- |
| Flutter | Cross-platform UI development |
| Dart | Application programming language |
| Firebase Authentication | User authentication |
| Cloud Firestore | Cloud database and real-time updates |
| Cubit / flutter_bloc | State management |

## 📁 Project Structure

```text
lib/
├── cubits/
│   ├── chat_screen/
│   ├── register_screen/
│   └── sign_in_screen/
├── models/
│   ├── sender_model.dart
│   └── user_model.dart
├── screens/
│   ├── chat_screen.dart
│   ├── register_screen.dart
│   ├── sign_in_screen.dart
│   └── welcome_screen.dart
├── widgets/
│   ├── custom_button.dart
│   ├── custom_text_field.dart
│   └── message.dart
├── firebase_options.dart
└── main.dart
```

## 🚀 Getting Started

### Prerequisites

- Flutter SDK installed and configured.
- Dart SDK compatible with the project's Flutter version.
- A Firebase project.
- An Android emulator, iOS simulator, or physical device.

### 1. Clone the repository

```bash
git clone https://github.com/Mohamed-Jalab/flutter-chat-me.git
cd flutter-chat-me
```

### 2. Install dependencies

```bash
flutter pub get
```

### 3. Configure Firebase

Create a Firebase project and register your application using the FlutterFire CLI.

```bash
dart pub global activate flutterfire_cli
flutterfire configure
```

Enable **Firebase Authentication** with the sign-in methods used by the application, and create a **Cloud Firestore** database.

Configure Firestore security rules before running the application. Never rely on the mobile application's UI to enforce database permissions.

### 4. Run the application

```bash
flutter run
```

## 🧠 What You Can Learn

This project can help beginners and junior Flutter developers explore:

- Firebase Authentication integration.
- Reading and writing documents in Cloud Firestore.
- Real-time data streams.
- Cubit-based state management.
- Separating screens, widgets, models, and state management logic.
- Structuring a small Flutter application.

## 🗺️ Roadmap

Planned improvements:

- [ ] Improve error handling and loading states.
- [ ] Add automated tests.
- [ ] Improve message list performance and pagination.
- [ ] Add user profile management.
- [ ] Add individual conversations.
- [ ] Improve accessibility and responsive UI.
- [ ] Add CI checks for formatting, analysis, and tests.

## 🐛 Issues and Feedback

Found a bug or have an idea for improvement? Open an issue with steps to reproduce the problem or a clear description of your proposal.

## 📄 License

This project is licensed under the [MIT License](LICENSE).

You are free to use, modify, and distribute this project according to the terms of the license.

---

**Built with Flutter 💙**

If you find this project useful for learning, consider giving the repository a star.
