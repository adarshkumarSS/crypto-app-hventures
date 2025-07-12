# React Native App

This is a basic React Native application built using the React Native CLI with TypeScript support.

---

## 📦 Requirements

Before you begin, make sure you have the following installed:

- Node.js (>= 18.x)
- npm or yarn
- JDK 17 or 20
- Android Studio with:
  - SDK & Emulator
  - ANDROID_HOME properly set
- React Native CLI

---

## 🔧 Installation

```bash
# 1. Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# 2. Install dependencies
npm install
# or
yarn install
```

▶️ Running the App
Start Metro Bundler
```bash
npx react-native start
```
In a new terminal: Run the app on Android
```bash
npx react-native run-android
Make sure an emulator is running or a device is connected.
```

💡 Useful Commands
```bash
# Clean Android build
cd android && ./gradlew clean

# Reset Metro cache
npx react-native start --reset-cache

# Kill process on 8081 if stuck
npx kill-port 8081
```

