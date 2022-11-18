# React Native - Authentication
Demo application to learn React Native, with authentication and authorization.

The app has Login and Register screens. After the user inputs their credentials, the app will redirect them to the Welcome screen.

The Welcome screen performs a get request to Firebase to retrieve protected data and shows its content on screen.

The authentication is handled by Firebase. Please set you firebase API key in the `/util/auth.js` file, and create a message key in the Realtime Database.
