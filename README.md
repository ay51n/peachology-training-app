# Peachology Mobile App

Peachology is an iOS and Android app built with Expo and React Native. This project targets phones only; it does not include a website or web build.

## Run the app

1. Install Node.js and Expo Go on your iPhone or Android phone.
2. In this project folder, run `npm install` and then `npx expo start`.
3. Scan the QR code with Expo Go (Android) or the iPhone Camera app.

## Build installable apps

Use Expo Application Services (EAS) for device builds:

- Preview build: `npx eas-cli build --platform all --profile preview`
- Store build: `npx eas-cli build --platform all --profile production`

Store publishing also requires Apple Developer and Google Play developer accounts. App Store and Play Store submission happen through their respective consoles after building.

## Included

- Native phone navigation with Home, Learn, Build, and Community tabs.
- Entrepreneurship courses, lesson outlines, and progress indicators.
- A three-step business idea planner saved on-device with AsyncStorage.
- A community feed and local post composer.

This prototype does not yet have accounts, cloud synchronization, instructor tools, or server-backed community. Vercel does not build native iOS or Android binaries; use EAS Build for those. The previous web/PWA source files have been removed.

## Stack

- Expo SDK 58 and React Native 0.88.
- `@react-native-async-storage/async-storage` for on-device plan persistence.
