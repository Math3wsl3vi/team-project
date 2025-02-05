
# Hospital Management System (HMS) with Medication Follow-up App

This project aims to develop a comprehensive **Hospital Management System (HMS)** integrated with a **follow-up app** to ensure medication adherence, improve patient care, and streamline hospital operations from patient registration to pharmacy services. The HMS will offer a seamless interface for managing patient data, appointments, prescriptions, and more. The follow-up app will provide timely medication reminders, ensuring patients stay on track with their prescribed treatment plans.

## Features
- **Patient Registration**: Seamless registration and tracking of patient details.
- **Appointment Scheduling**: Allows patients to book appointments with doctors.
- **Medication Management**: Prescription tracking, medication schedules, and reminder notifications.
- **Pharmacy Integration**: Tracks prescribed medications and ensures timely dispensing.
- **Follow-up App**: A dedicated app that reminds patients to take their medication on time and stores prescription history.

---

## Tech Stack

### **Web Application**

- **Frontend**:
  - **React**: A JavaScript library for building user interfaces. Used for the dynamic and responsive web front-end.
  - **Next.js**: React framework for server-side rendering and building scalable web applications.
  - **TypeScript**: A superset of JavaScript that provides static typing, enhancing development efficiency and reducing bugs.

- **Backend**:
  - **Express.js**: A fast, unopinionated web framework for Node.js. Handles HTTP requests and API routing.
  - **Firebase**: Used for authentication, real-time database, and cloud storage. Firebase Firestore is used for managing and storing data.

- **Database**:
  - **Firestore (Firebase)**: NoSQL cloud database for flexible and scalable data storage.
  
- **State Management**:
  - **Zustand**: A state management library for React applications, used to handle the app’s global state.

- **Authentication**:
  - **Firebase Authentication**: Handles user registration, login, and session management securely.

---

### **Android Application (Follow-up App)**

- **Frontend**:
  - **React Native/Flutter**: A framework for building native mobile applications using JavaScript and React. It allows for building iOS and Android apps with a single codebase.
  
- **State Management**:
  - **Zustand**: Used to manage the application’s state, ensuring consistent data flow across screens.

- **Backend**:
  - **Firebase**: Used for real-time updates on prescription data, user authentication, and managing medication reminders.

- **Push Notifications**:
  - **Firebase Cloud Messaging (FCM)**: Handles the push notifications for medication reminders, ensuring patients are notified at the right time.

---

## Getting Started

### **Prerequisites**

Before running the project locally, ensure that you have the following installed:
- **Node.js** (>=12.x)
- **npm** or **yarn**
- **React Native CLI** (for Android development)
- **Android Studio** (for Android emulator)

### **Installation for Web App**

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hms-followup-app.git
   cd hms-followup-app
   ```

2. Install the dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Visit `http://localhost:3000` to view the app.

### **Installation for Android App**

1. Clone the repository:
   ```bash
   git clone https://github.com/Math3wsl3vi/team-project.git
   cd team-project
   ```

2. Install the dependencies:
   ```bash
   npm install
   # or
   yarn install
   ```

3. Run the app on Android:
   ```bash
   npm run android
   # or
   yarn android
   ```

4. This will build the app and launch it on the Android emulator or connected device.

---

## Contributing

We welcome contributions to this project! If you'd like to help, please fork the repository, create a new branch, and submit a pull request with your changes. Ensure that your code is well-documented and follows the existing code style.

---

## License

This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

## Contact

For any queries or suggestions, please reach out to us.

---
Happy Hacking!
