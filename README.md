# TODOIST

This is a simple todo application built with React Native, Expo, and Convex. I created this as a pet project to practice my mobile development skills.

<div style="display: flex; justify-content: center; align-items: center; margin-bottom: 20px;">
<img src="./assets/demo.gif" alt="Todoist Demo" height="500" />
</div>

## Features

- Add new todos
- Mark todos as complete
- Clear all todos
- Light and dark mode support
- Settings page to reset the app

## Tech Stack

- **Frontend:** React Native with Expo
- **Backend:** Convex
- **Language:** TypeScript
- **Navigation:** React Navigation
- **Styling:** Custom stylesheets with `expo-linear-gradient`

## Installation

You can install the app on your Android device by downloading the latest APK from our [releases page](https://github.com/2SSK/todoist/releases).

1.  Go to the releases page.
2.  Download the `.apk` file from the latest release.
3.  Open the downloaded file on your Android device to install it.

## Contributing

We welcome contributions from the community! If you'd like to contribute, please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with a clear message.
4.  Push your changes to your fork.
5.  Create a pull request to the main repository.

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Project Structure

```
.
├── app/              # Expo Router pages
├── assets/           # Fonts, images, and styles
├── convex/           # Convex backend schema and functions
├── hooks/            # Custom hooks
├── _components/      # Reusable components
├── scripts/          # Node.js scripts
├── .env.example      # Example environment variables
├── app.json          # Expo configuration
├── package.json      # Project dependencies
└── tsconfig.json     # TypeScript configuration
```

## Scripts

- `npm start`: Starts the Expo development server.
- `npm run android`: Starts the app on a connected Android device or emulator.
- `npm run ios`: Starts the app on the iOS simulator.
- `npm run web`: Starts the app in a web browser.
- `npm run lint`: Lints the project files using ESLint.
- `npm run reset-project`: Resets the project to its initial state.

## Deployment

This project is configured for deployment with [Expo Application Services (EAS)](https.expo.dev/eas). To build and submit your app, refer to the EAS documentation.
