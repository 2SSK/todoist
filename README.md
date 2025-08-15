# React Native Todo App

This is a simple todo application built with React Native, Expo, and Convex. I created this as a pet project to practice my mobile development skills.

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

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- Expo CLI
- A free Convex account

### Installation

1.  Clone the repository:

    ```bash
    git clone https://github.com/2SSK/todoist.git
    cd todoist
    ```

2.  Install the dependencies:
    ```bash
    npm install
    ```

### Configuration

1.  Create a new Convex project.
2.  Copy the `.env.example` file to a new file named `.env`:
    ```bash
    cp .env.example .env
    ```
3.  In your Convex project dashboard, go to "Settings" and copy your "Deployment URL".
4.  Paste the URL into your `.env` file:
    ```
    CONVEX_URL=https://your-deployment-name.convex.cloud
    ```

### Running the App

1.  Start the development server:
    ```bash
    npm start
    ```
2.  Follow the instructions in the terminal to run the app on an Android emulator, iOS simulator, or on the web.

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
