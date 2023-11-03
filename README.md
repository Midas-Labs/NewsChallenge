
# React Native Authentication and News App Challenge

## Background
Create a simple news application using React Native that fetches news articles from a public API. The app will require users to sign in to view the articles and should handle different states like loading, success, and error.

## Requirements

### 1. Setup
- Initialize a new React Native project using React Native CLI.
- Use functional components with React hooks.

### 2. Authentication
- Integrate user authentication with Auth0 or Clerk.(Create a free account)
- Users should be able to sign up, sign in, and sign out.
- Ensure the news feed is only accessible to authenticated users.

### 3. API Integration
- Use any free news API, such as [NewsAPI](https://newsapi.org/), to fetch top headlines.
- Fetch top headlines after a user has successfully signed in.

### 4. Error Handling
- Implement error handling for the authentication process and API requests.
- Display user-friendly error messages for different errors.
- Include a retry mechanism for failed API requests.

### 5. State Management
- Manage the application's state for loading, success, error, and authentication status.

### 6. UI/UX
- Create a login/sign-up screen with input validation.
- Display an activity indicator during loading states.
- Render the list of articles with their title, description, and thumbnail.

### 7. Bonus Features
- Implement infinite scroll for the news feed.
- Allow users to filter articles by categories.
- Add biometric authentication as a second factor after sign-in.

### 8. Testing
- Write Jest unit tests for the authentication process, ensuring that the user can sign up, sign in, and sign out.
- Write Jest unit tests for API calls, ensuring that articles are fetched correctly, and that the error handling logic is triggered when the API call fails.
- Ensure tests cover the retry mechanism and state changes throughout the application.

## Deliverables
- Source code in a GitHub repository.
- README documentation on setup, third-party libraries, and running tests.
- Video or GIF of the app's functionality, including authentication and error handling.
- A test suite with sufficient coverage for the authentication and API integration parts of the app.

## Evaluation Criteria
- Correctness of functionality.
- Code quality and organization.
- Seamless integration of authentication.
- Graceful error handling.
- Efficient state management.
- Smooth and intuitive user experience.
- Test coverage and successful test execution.

## Additional Instructions
- Use JavaScript ES6+ syntax.
- Use Context API or another state management library/tool.
- Implement navigation with React Navigation.
- Follow setup instructions for Auth0 or Clerk.
- Write tests for authentication flow and API calls with Jest.

## For A Sample Task Board 
Here is a list of the sample tasks provided, feel free to modify them as needed. Make sure that all the tasks are being tracked using github issues.
| Ticket # | Summary                                           | Issue Type | Description                                                                                                                                          | Acceptance Criteria                                                                                                                                                                                           |
|----------|---------------------------------------------------|------------|------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1        | Project Setup and Configuration                   | Task       | The developer needs to create a new React Native project, ensuring all necessary tools and dependencies are properly installed and configured.        | - Project initializes without errors.<br>- A `README.md` file is created with setup instructions.                                                                                                             |
| 2        | Integrate Auth0/Clerk for Authentication          | Task       | Integrate Auth0 or Clerk for user authentication, enabling users to sign up, sign in, and sign out.                                                  | - Auth0/Clerk is properly configured in the app.<br>- Users can sign up, sign in, and sign out.<br>- Authentication state is managed correctly.                                                                |
| 3        | API Integration for Fetching News                 | Task       | Integrate a news API service to fetch top headlines, available only to authenticated users.                                                          | - The News API integration functions correctly.<br>- Only authenticated users can fetch news articles.<br>- The fetched data should include the article's title, description, and image if available.         |
| 4        | Implement Error Handling Mechanisms               | Task       | Develop a robust error handling system for both the authentication flow and the news API requests.                                                   | - Error messages are user-friendly.<br>- There is a retry option for failed API requests.<br>- Authentication errors are handled gracefully.                                                                  |
| 5        | Implement State Management                        | Task       | Implement state management to handle loading, success, error, and authentication status.                                                             | - Appropriate use of state management patterns.<br>- The UI reflects the different states accurately.<br>- The app remains responsive during state transitions.                                               |
| 6        | Develop the UI/UX for Authentication             | Task       | Create UI components for the login and sign-up screens, including input validation and feedback.                                                     | - Screens for login and signup are created.<br>- Input validation works and provides feedback.<br>- A logout option is accessible and functional.                                                              |
| 7        | Develop the UI/UX for News Feed                   | Task       | Develop the UI for displaying news articles with an activity indicator during loading states and the ability to pull-to-refresh.                     | - News articles are displayed in a list.<br>- An activity indicator is shown during loading.<br>- Pull-to-refresh functionality is implemented.                                                               |
| 8        | Implement Additional Features                     | Task       | Add infinite scroll for the news feed and allow users to filter articles by categories.                                                              | - Infinite scroll loads more articles as the user scrolls down.<br>- Users can filter articles by selected categories.                                                                                        |
| 9        | Add Biometric Authentication                      | Task       | Implement biometric authentication as a second factor after the user has signed in.                                                                  | - Biometric authentication is prompted after the initial sign-in.<br>- The feature works on supported devices.                                                                                                |
| 10       | Write Unit Tests Using Jest                       | Task       | Create a suite of unit tests for the authentication flow and the API calls to ensure they function as expected.                                      | - Tests cover critical authentication functionality.<br>- Tests cover API call success and failure cases.<br>- All tests pass with clear documentation on how to run them.                                     |

https://docs.google.com/spreadsheets/d/1fNAJZRa1lGDPZg3viFOCPYkUMPkKrvLx-UyBTVLsaZE/edit?usp=sharing


[![npm version](https://img.shields.io/npm/v/react-native-typescript-boilerplate.svg?style=for-the-badge)](https://www.npmjs.com/package/@freakycoder/react-native-typescript-boilerplate)
[![npm](https://img.shields.io/npm/dt/react-native-typescript-boilerplate.svg?style=for-the-badge)](https://www.npmjs.com/package/@freakycoder/react-native-typescript-boilerplate)
![Platform - Android and iOS](https://img.shields.io/badge/platform-Android%20%7C%20iOS-blue.svg?style=for-the-badge)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![styled with prettier](https://img.shields.io/badge/styled_with-prettier-ff69b4.svg?style=for-the-badge)](https://github.com/prettier/prettier)



We're proudly announce that `Version 3.5` is here!

- Native Splash Screen
- New React Native Architecture Ready **(RN 0.71+)** 🍻
- Awesome Theme Support for both Light / Dark Mode 🌙
- Latest `React` and `React Native` Dependencies 🌟
- All Dependencies are Upgraded
- New GIF with the Project Example for Theming
- Much Better Documentation
- Detailed Roadmap

# 🐶 What's Included?

- **Typescript**
- **Flipper Ready**
- **Navigation System**
  - [React Navigation 6](https://reactnavigation.org/blog/2021/08/14/react-navigation-6.0/)
  - [React Navigation Helpers](https://github.com/WrathChaos/react-navigation-helpers)
  - Ready to use Stack and Tab Screens with navigation
- **NEW: Built-in Theme System with Hooks**
  - ☀️ Light Theme Support
  - 🌙 Dark Theme Support
  - Dynamic Color Palette System
  - Custom Font Support
  - Built-in Better `Text` Component
- **Ready to use [React Native Reanimated 2](https://docs.swmansion.com/react-native-reanimated/) Integration**
- **Native Splash Screen Integration**
  - [React Native Splash Screen](https://github.com/crazycodeboy/react-native-splash-screen)
- **Awesome [React Native Helpers](https://github.com/WrathChaos/react-native-helpers) Integration**
  - Noth Detection Support
  - Better Dimension Helper (Ex: ScreenWidth, ScreenHeight)
  - Cool Text Helpers
- **React Native Vector Icons**
  - [React Native Vector Icons](https://github.com/oblador/react-native-vector-icons)
  - [React Native Dynamic Vector Icons](https://github.com/WrathChaos/react-native-dynamic-vector-icons)
- **[Localization](https://github.com/stefalda/ReactNativeLocalization) (Multi-Language Support)**
- **HTTP Network Management**
  - [Axios](https://github.com/axios/axios)
  - [Axios Hooks](https://github.com/simoneb/axios-hooks)
  - API Service with Usage Examples
- **Built-in EventEmitter**
  - [EventBus](https://github.com/browserify/events#readme)
- **Babel Plugin Module Resolver**
  - Fixing the relative path problem
  - Visit `.babelrc` to ready to use and more customization
- **Pre-commit Husky Integration**
  - Ready to command husky setup with `npm run husky:setup`
  - `commitlint` Integration for better commit linter
  - Auto prettier on pre-commit
  - Awesome ESLint Integration
- **Built-in Custom Font Implementation**
  - All you need to do is copy-paste the .tff files into `assets/fonts` folder
  - Run `npx react-native-asset` command

- **More and more! :)**

# 🚀 Getting Started

## Quick Start

To create a new project using the barebone boilerplate:


# 🎯 Step By Step Guide

## Clean-Up & Simple Run

Clean up the files from the example repository and do not forget to install the dependencies
There is a good example by default on `HomeScreen`. You can delete the all screens.

- `npm i`
- `npm run clean-up`
- `npm i && npx pod-install`
- `react-native run-ios/android`

**OR**

- `rm -rf .git README.md`
- `rm -rf ./assets`
- `git init`
- `npm i`
- `npm run husky:setup`
- `npx pod-install` (iOS Only)
- `react-native run-ios/android`

## Husky Integration

Before doing anything else, please simply run the command to initalize the husky. If you do not run clean-up part you should run the husky setup by yourself

```jsx
npm run husky:setup
```

`husky:setup` will handle the initialization, installation and ready to use `commitlint`, `prettier` and `eslint`.

## Rename the project: (Thanks to [react-native-name](https://github.com/junedomingo/react-native-rename))

```sh
npx react-native-rename <your-project-name>
```

> With custom Bundle Identifier (Android only. For iOS, please use Xcode)

```sj
npx react-native-rename <your-project-name> -b <bundleIdentifier>
```

### Install Pods (iOS Only)

- `npm i`
- `cd ios && pod install`
- `cd .. && react-native run-ios/android`

### Android local.properties (Android Only)

- `npm i`
- `cd android && mkdir local.properties`
- `nano local.properties`

#### Example of MacOS Android SDK Path

Make sure that set your right path of Android **SDK**

##### MacOS / Linux

Replace your machine name instead of `username`

```
sdk.dir=/Users/username/Library/Android/sdk
```

##### Windows

Replace your machine name instead of `username`

```
sdk.dir=/Users/username/Library/Android/sdk
```

- `cd .. & react-native run-ios/android`

# 📃 Documentations

- [Components](./docs/components.md)
- [Axios Hooks](./docs/axios-hooks.md)
- [Event Emitter Usage](./docs/event-emitter.md)
- [Project Structure](./docs/project-structure.md)

## License

React Native Typescript Boilerplate is available under the MIT license. See the LICENSE file for more info.
