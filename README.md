# ProjetWS 📱

An Android application built in Java that records data using web services.

## 📋 Overview

ProjetWS is a native Android application developed in Java. It interacts with a web service (WS) to record and manage data from the mobile device.

## 🛠️ Tech Stack

- **Language:** Java
- **Platform:** Android
- **Build Tool:** Gradle (Kotlin DSL — `build.gradle.kts`)
- **IDE:** Android Studio (IntelliJ-based)

## 📁 Project Structure

```
projetws/
├── app/                        # Main application module
│   └── src/
│       └── main/
│           ├── java/           # Java source files
│           ├── res/            # Resources (layouts, drawables, strings…)
│           └── AndroidManifest.xml
├── gradle/                     # Gradle wrapper files
├── build.gradle.kts            # Root build configuration
├── settings.gradle.kts         # Project settings
└── gradle.properties           # Gradle properties
```

## 🚀 Getting Started

### Prerequisites

- [Android Studio](https://developer.android.com/studio) (latest stable version recommended)
- Android SDK (API level as defined in `build.gradle.kts`)
- Java 11 or higher

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/M4l1k40/projetws.git
   cd projetws
   ```

2. **Open in Android Studio:**
   - Launch Android Studio
   - Select **File > Open** and navigate to the cloned folder

3. **Sync Gradle:**
   - Android Studio will prompt you to sync Gradle — click **Sync Now**

4. **Run the app:**
   - Connect an Android device or start an emulator
   - Click the **Run ▶** button or use `Shift + F10`

### Build from Command Line

```bash
# Debug build
./gradlew assembleDebug

# Release build
./gradlew assembleRelease
```

The generated APK will be found in `app/build/outputs/apk/`.

## 📦 Dependencies

Dependencies are declared in `app/build.gradle.kts`. Refer to that file for the full list of libraries used.

## l'app enregistre :
https://github.com/user-attachments/assets/ade017ea-dc8a-49ca-8445-7e57e8f22295
