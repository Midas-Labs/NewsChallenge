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

