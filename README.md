# AndroidCalculator

A native Android calculator application developed in **Java** using **Android Studio**.

---

## Overview

**AndroidCalculator** is a clean, responsive mobile calculator built for the Android platform. It provides everyday arithmetic functionality with instant visual feedback and support for both standard and high-density Android displays.

---

## Features

- **Arithmetic Operations**: Addition, subtraction, multiplication, and division.
- **Expression Display**: Clean numeric input handling with decimal support and negative value handling.
- **Clear & Delete**: Single-character backspace and full calculation reset.
- **Responsive Layout**: Designed to adapt cleanly across diverse Android screen sizes and orientations.

---

## Tech Stack

- **Platform**: Android (minSdkVersion compatible with modern Android releases)
- **Language**: Java
- **IDE**: Android Studio
- **Build System**: Gradle

---

## Project Structure

```text
AndroidCalculator/
├── app/
│   ├── build.gradle
│   └── src/
│       └── main/
│           ├── java/           # Activity controllers and calculation logic
│           ├── res/
│           │   ├── layout/     # XML UI layouts
│           │   └── values/     # Colors, strings, and theme definitions
│           └── AndroidManifest.xml
├── gradle/
└── build.gradle
```

---

## Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (Electric Eel or newer recommended)
- Android SDK with Platform Tools
- Java Development Kit (JDK 11+)

### Building and Running

1. Clone the repository:
   ```bash
   git clone https://github.com/Rhuan09/AndroidCalculator.git
   cd AndroidCalculator
   ```
2. Open Android Studio and select **Open**, navigating to the cloned directory.
3. Allow Gradle to download dependencies and sync the project.
4. Launch an Android Virtual Device (AVD) emulator or connect a physical Android device with USB debugging enabled.
5. Click **Run** (`Shift + F10`) to deploy and test.

---

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
