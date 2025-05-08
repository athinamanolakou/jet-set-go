# ✈️ JetSetGo

**JetSetGo** is a smart travel companion app built with Flutter and Firebase, designed to help users organize their trips with ease. It includes features for packing, document management, weather previews, and itinerary planning. 

---

## Features

-  Smart packing lists stored in Firestore
-  Upload and view travel documents using URL launcher
-  Minimalist weather widget for current-day forecasts
-  Daily itinerary planning with calendar support
-  Firebase Authentication for secure access
-  Custom UI design with a peach-and-dark theme

---

## To run this project locally:

```bash
git clone git@github.com:athinamanolakou/jet-set-go.git
cd jet-set-go
flutter pub get
flutter run
```

note: Make sure you have Flutter installed and connected to a device or simulator.

## Tech Stack
- Flutter & Dart
- Firebase (Authentication, Firestore, Storage)
- URL Launcher
- Custom Components for UI and navigation
- OpenWeather API (for live weather data)
- Gemini API (for AI-powered suggestions)


## Project Structure 

```plaintext
jetsetgo/
├── android/                // Android platform-specific code
├── ios/                    // iOS platform-specific code
├── web/                    // Web support
├── macos/                  // macOS support
├── linux/                  // Linux support
├── windows/                // Windows support
├── assets/                 // Fonts and images
│    ├── fonts/
│    └── images/
├── lib/                    // Dart code (core app logic)
│    ├── components/        // Reusable UI components
│    ├── pages/             // Screens like home, login, profile
│    ├── utils/             // Helper classes (weather API, AI helpers)
│    └── main.dart          // App entry point
├── pubspec.yaml            // Flutter dependencies
├── pubspec.lock            // Dependency versions lock file
├── .gitignore              // Git ignored files
└── README.md               // Project overview
```


note: This project is intended for educational and portfolio use only.

Maintained by Athina Manolakou
