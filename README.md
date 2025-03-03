# Affirmations App

## Overview
A simple Android application that displays a list of affirmations with images. This project demonstrates basic Android development concepts using Kotlin and Jetpack Compose, including UI elements, data binding, and theming.

## Features
- Scrollable list of affirmations
- Each affirmation is displayed with an image and text
- Simple, intuitive user interface
- Dynamic theming support

## Screenshots
![image](https://github.com/user-attachments/assets/f67b3865-4c4d-43eb-b96d-99c3fafe72f2)


## Technologies Used
- Kotlin
- Android SDK
- Jetpack Compose
- Gradle

## Prerequisites
- Android Studio Arctic Fox (2020.3.1) or newer
- Android SDK version 21+
- Gradle 7.0+
- JDK 11

## Setup Instructions

### Clone the Repository
```bash
git clone https://github.com/yourusername/affirmations.git
cd affirmations
```

### Open and Build in Android Studio
1. Open Android Studio
2. Select "Open an existing Android Studio project"
3. Navigate to the cloned repository and click "Open"
4. Wait for the project to sync and build
5. Connect an Android device or use the emulator

### Run the Application
- Click the "Run" button (green triangle) in Android Studio
- Select a deployment target (emulator or connected device)
- The app should install and launch automatically

## How to Use
1. Launch the Affirmations app
2. The main screen displays a list of affirmations with images
3. Scroll through the list to view different affirmations

## Project Structure
```
app/
├── src/main/
│   ├── java/com/example/affirmations/
│   │   ├── data/
│   │   │   └── Datasource.kt       # Data source for affirmations
│   │   ├── model/
│   │   │   └── Affirmation.kt      # Data model for affirmation
│   │   ├── ui/theme/
│   │   │   ├── Color.kt            # Color definitions
│   │   │   ├── Theme.kt            # Theme definitions
│   │   └── MainActivity.kt         # Main activity with UI logic
│   ├── res/
│   │   ├── drawable/               # Image resources
│   │   ├── layout/                 # Layout resources
│   │   ├── values/                 # String and color resources
│   └── AndroidManifest.xml         # App configuration
└── build.gradle                    # App module build configuration
```

## Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Learning Resources
- [Android Basics in Kotlin](https://developer.android.com/courses/android-basics-kotlin/course)
- [Kotlin Programming Language](https://kotlinlang.org/docs/home.html)
- [Android Developers Documentation](https://developer.android.com/docs)

## License
This project is licensed under the Apache License 2.0 - see the LICENSE file for details.

## Acknowledgements
- Android Developers documentation and tutorials
- [Material Design](https://material.io/design) for UI inspiration

---
*This app was created as part of the Android Basics in Kotlin course, demonstrating fundamental Android development concepts.*
