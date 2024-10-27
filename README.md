
# Product Delivery Estimator App

This project is a **React Native** application designed to manage a catalog of 5,000 products and service 25,000 pincodes. The app calculates and displays estimated delivery dates based on the user-selected product and entered pincode, in coordination with associated logistics providers. The app handles various scenarios, such as invalid pincodes, out-of-stock products, and cutoff times for same-day delivery, ensuring a user-friendly and responsive UI.

---

## Getting Started

**Note:** Make sure you have completed the React Native environment setup until the "Creating a new application" step.

### Step 1: Start the Metro Server

First, start **Metro**, the JavaScript bundler included with React Native.

Run the following command from the root of the project:

```bash
# Using npm
npm start

# OR using Yarn
yarn start
```

### Step 2: Start the Application

Let Metro Bundler run in its terminal. In a new terminal, from the root of your project, use the following command to launch the app on an Android or iOS emulator:

**For Android:**

```bash
# Using npm
npm run android

# OR using Yarn
yarn android
```

**For iOS:**

```bash
# Using npm
npm run ios

# OR using Yarn
yarn ios
```

Once set up, you should see the app running on your Android Emulator or iOS Simulator, provided your environment setup is correct.

> You can also launch the app directly from **Android Studio** or **Xcode**.

### Step 3: Modify the Application

After successfully launching the app, open `App.tsx` in your preferred text editor to start making changes.

- **For Android**: Press the `R` key twice or select "Reload" from the Developer Menu (`Ctrl + M` on Windows/Linux or `Cmd ⌘ + M` on macOS) to see updates.
- **For iOS**: Use `Cmd ⌘ + R` in the iOS Simulator to reload.

---

## Key Features

- **Product Selection and Delivery Estimation**: Select a product and enter a pincode to receive an estimated delivery date.
- **Error Handling**:
  - Invalid pincode entries.
  - Out-of-stock products.
  - Missing cutoff times for same-day delivery.
- **Responsive, User-Friendly Interface**: Built with an emphasis on UI/UX best practices to ensure smooth and intuitive user interactions.

---

## Additional Resources

For more information, consult the following resources:

- [React Native Website](https://reactnative.dev/)
- [Getting Started Guide](https://reactnative.dev/docs/getting-started)
- [React Native Blog](https://reactnative.dev/blog)
- [React Native GitHub Repository](https://github.com/facebook/react-native)

---

## Troubleshooting

If you encounter issues, consult the [React Native Troubleshooting Guide](https://reactnative.dev/docs/troubleshooting).

created by: Kulashekar Inkollu

