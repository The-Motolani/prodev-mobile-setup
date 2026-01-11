# First Mobile App Setup with Expo Router

## Objective

To scaffold a React Native application using the Expo Router template, understand the file structure, and run the app on a physical device using Expo Go.

## Project Scaffolding Steps

1. Navigated to the parent directory:

   ```bash
   cd prodev-mobile-setup
   ```

2. Created and navigated into a new folder:

```bash
   mkdir prodev-mobile-app-0x00
   cd prodev-mobile-app-0x00
```

3. Initialized a new Expo app using Expo Router:

```bash
   npx create-expo-app@latest .
```

4. Modified the home screen

- Opened app/(tabs)/index.tsx

- Replaced the default text `Welcome!` with `First App Created`.

5. Ran the app:

 ```bash
 npx expo start
 ```

 6. Scanned QR code using Expo Go

The application successfully rendered on my physical device.

