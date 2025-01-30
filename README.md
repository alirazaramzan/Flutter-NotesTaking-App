# Notes Keeper - A Flutter Notes App

## 📌 Overview
Notes Taking is a simple and efficient note-taking app built using Flutter. It allows users to add, edit, and manage notes seamlessly with an intuitive user interface. The app also features user authentication and a customizable theme option to enhance the user experience.

## ✨ Features
- 📝 **Add and Edit Notes** - Create and modify notes with ease.
- 🔒 **User Authentication** - Secure login and signup using Firebase authentication.
- 🎨 **Theme Customization** - Switch between light and dark themes.
- 📂 **Persistent Storage** - Notes are saved locally using a database.
- 🔍 **Search Functionality** - Find notes quickly with a search bar.
- 📤 **Cloud Sync** - Sync notes to Firebase Firestore for backup.
- 🎯 **Responsive UI** - Works seamlessly across different screen sizes.

## 🛠️ Tech Stack
- **Framework**: Flutter (Dart)
- **State Management**: Provider (or Riverpod, depending on implementation)
- **Database**: Hive (for local storage) / Firebase Firestore (for cloud sync)
- **Authentication**: Firebase Auth
- **UI Components**: Material Design

## 📸 Screenshots
![Screenshot1](assets/screenshots/screenshot1.png)
![Screenshot2](assets/screenshots/screenshot2.png)
![Screenshot3](assets/screenshots/screenshot3.png)

## 🚀 Getting Started
### Prerequisites
Ensure you have the following installed:
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart](https://dart.dev/get-dart)
- [Android Studio](https://developer.android.com/studio) or [VS Code](https://code.visualstudio.com/)
- Firebase setup (for authentication and cloud sync, if enabled)

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/flutter-notes-app.git
   cd flutter-notes-app
   ```
2. Install dependencies:
   ```sh
   flutter pub get
   ```
3. Run the app:
   ```sh
   flutter run
   ```

## 📁 Project Structure
```
flutter-notes-app/
│-- lib/
│   ├── main.dart
│   ├── screens/
│   │   ├── home_screen.dart
│   │   ├── note_editor.dart
│   ├── models/
│   │   ├── note_model.dart
│   ├── services/
│   │   ├── auth_service.dart
│   │   ├── database_service.dart
│   ├── providers/
│   │   ├── theme_provider.dart
│   │   ├── notes_provider.dart
│   ├── widgets/
│   │   ├── note_card.dart
│   ├── utils/
│       ├── constants.dart
│       ├── themes.dart
│-- assets/
│-- pubspec.yaml
│-- README.md
```

## 🔑 Firebase Setup
To enable authentication and cloud sync:
1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. Enable Firebase Authentication (Email/Password).
3. Add Firebase to your Flutter project:
   ```sh
   flutterfire configure
   ```
4. Enable Firestore for cloud syncing (if needed).
5. Update `google-services.json` (Android) and `GoogleService-Info.plist` (iOS) in the respective folders.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## 📬 Contact
For any inquiries, reach out at [your.email@example.com](mailto:your.email@example.com) or open an issue in the repository.

---



![2](https://github.com/user-attachments/assets/86c1ac74-c1dc-420c-8bb7-bd33e5ec02bf)
![1](https://github.com/user-attachments/assets/d3bac231-38bd-4930-b709-8ece7f7c22ce)
