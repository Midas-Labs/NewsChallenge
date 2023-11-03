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
