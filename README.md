# Shoppe Men — Men's Fashion Store

AppStorm university project: a React Native / Expo Router shopping demo with **30 distinct screens** in one main `ShoppeMen.js` file.

## Platforms
- iOS / Android via Expo Go (compatible Expo SDK required)
- Web via React Native Web

## Tech
React Native, Expo, Expo Router, JavaScript, TypeScript route wrappers, React Hooks, AsyncStorage, Expo Linear Gradient.

## Screens
Splash, Onboarding (3 slides), Login, Register, Forgot Password, Verify Code, Reset Password, Password Success, Welcome, Profile Setup, Home, Shop, Categories, Category Products, Search, Search Results, Product Details, Product Gallery, Favorites, Cart, Checkout, Order Success, My Orders, Notifications, Profile, Edit Profile, Settings, Live Shopping, Fashion Stories, Story Details.

## Install
```bash
npx create-expo-app@latest ShoppeMen --template blank
cd ShoppeMen
npx expo install expo-router react-native-screens react-native-safe-area-context expo-linking expo-constants expo-status-bar react-native-web react-dom @expo/metro-runtime expo-linear-gradient @react-native-async-storage/async-storage
```
Copy the files in this package into the project root, then ensure `package.json` has `"main": "expo-router/entry"` and run `npx expo start --clear`.

## Demo behavior
Authentication is **local demo only** (no backend). Registered credentials and profile, cart, favorites, notifications and orders are stored locally via AsyncStorage. Verification code: `1234`. Checkout is simulated and never charges money. Live shopping is a static simulated live view. Product photos are loaded remotely from Unsplash, so internet access is required.

## Author
AppStorm student project. Add your name here.
