# rn-assignment7-11011536

This React Native application is a mobile shopping app developed as part of the DCIT202 Mobile Application Development course. It allows users to browse products, view details, add items to a cart, and manage their shopping cart.

## Features

- **Product Listing:** Displays a list of products fetched from an external API.
- **Product Details:** Shows detailed information about a selected product.
- **Shopping Cart:**
  - Allows users to add and remove items.
  - Persists cart data using local storage.
- **Navigation:** Provides a drawer/tab navigation for easy access to screens.

## UI Design

The UI design for this app was based on the provided mockup. You can access it here: [UI Design Link]

## Project Structure

- **`components/`:** Contains reusable components for product items, buttons, etc.
- **`screens/`:** Houses the main screens (HomeScreen, ProductDetailScreen, CartScreen).
- **`navigation/`:** Handles the navigation setup (drawer/tab navigation).
- **`api/`:** Contains functions for fetching data from the external API.
- **`storage/`:** Manages local storage for cart data.
- **`App.js`:** The main entry point of the application.

## Getting Started

1.  **Clone the repository:**

    ```bash
    git clone [invalid URL removed]
    ```

2.  **Install dependencies:**

    ```bash
    cd rn-assignment7-ID
    npm install
    ```

3.  **Start the app:**
    ```bash
    npx expo start
    ```

- If you get the error "Cannot find module '@expo/metro-runtime' from 'node_modules/expo/AppEntry.js", then try installing "expo" by using:
  ```bash
  expo install expo
  ```
- Run `expo upgrade` to upgrade your project dependencies

4.  **Open the app in Expo Go:**
    - Download Expo Go on your iOS or Android device.
    - Scan the QR code displayed in the terminal to open the app.

## Design Choices

- **Navigation:** I chose to use [Drawer/Tab Navigation] because...
- **Local Storage:** I opted for [AsyncStorage/SecureStore/FileSystem] due to...

## Screenshots

(Include screenshots of your app running on a simulator/device here)

## Dependencies

- `expo`: The Expo SDK for building React Native apps.
- `react-navigation`: For navigation between screens.
- `@react-navigation/native`: Additional components for React Navigation.
- `@react-navigation/bottom-tabs`: For bottom tab navigation (if used).
- `@react-navigation/drawer`: For drawer navigation (if used).
- `axios` or `fetch`: For making API requests.
