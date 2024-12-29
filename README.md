# Expense Tracker App

## Description
This is a cross-platform Expense Tracking application built using React Native. It allows users to log, track, and categorize their expenses. The app utilizes Firebase for backend data storage and Redux for state management. The data fetched from Firebase is synced and stored locally using Redux, ensuring smooth and responsive user interactions.

---

## Features
- Add, edit, and delete expenses
- Categorize expenses
- View expense history
- Real-time data synchronization with Firebase
- Local state management using Redux for better performance

---

## Tech Stack
- **Frontend**: React Native
- **State Management**: Redux
- **Backend**: Firebase (Realtime Database or Firestore)

---

## Getting Started

### Prerequisites
Ensure you have the following installed on your system:
- Node.js
- React Native CLI or Expo CLI
- Firebase account

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/expense-tracker-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd expense-tracker-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

4. Configure Firebase:
   - Go to the Firebase Console.
   - Create a new project and set up a Realtime Database or Firestore.
   - Replace the `firebaseConfig` in the app with your Firebase project credentials.

5. Run the application:
   ```bash
   npm start
   ```
   Or if using Expo:
   ```bash
   expo start
   ```

---

## Folder Structure
```
expense-tracker-app/
├── src/
│   ├── components/         # Reusable components
│   ├── screens/            # App screens (Home, Add Expense, etc.)
│   ├── constants/          # Defined styles
│   ├── utls/               # Firebase configuration and API calls, Redux actions, reducers, and store
│   ├── assets/             # Images, fonts, and other assets
├── App.js                  # Main entry point
├── package.json            # Project dependencies
├── README.md               # Documentation
```

---

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.


---

## Acknowledgements
- React Native documentation
- Firebase documentation
- Redux documentation
