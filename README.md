# 📝 To-Do List App

A simple and elegant To-Do List application built with Expo and React Native.

## Features

- ✅ Add new tasks
- ✅ Mark tasks as complete/incomplete
- ✅ Delete tasks with confirmation
- ✅ Clear all completed tasks
- ✅ Persistent storage using AsyncStorage
- ✅ Dark theme UI
- ✅ Task counter (pending/completed)

## Screenshots

The app features a modern dark theme with:
- Clean input field for adding tasks
- Checkbox-style task completion
- Swipe-friendly delete button
- Empty state illustration

## Getting Started

### Prerequisites

- Node.js (v18 or newer)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)
- Expo Go app on your mobile device

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/todo-list.git
cd todo-list
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npx expo start
```

4. Scan the QR code with Expo Go (Android) or Camera app (iOS)

## Tech Stack

- **Expo** - React Native framework
- **React Native** - Mobile app framework
- **AsyncStorage** - Persistent local storage

## Project Structure

```
todo-list/
├── App.js              # Main application component
├── app.json            # Expo configuration
├── package.json        # Dependencies
├── assets/             # Icons and images
└── README.md           # Documentation
```

## Building for Production

### Android APK
```bash
eas build -p android --profile preview
```

### iOS
```bash
eas build -p ios --profile preview
```

## License

MIT License

## Author

Built with ❤️ using Expo
