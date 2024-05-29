# Flet Authentication App

This is a Flet-based application for user authentication and job posting management, integrated with Firebase for authentication and database services.

## Features

- User Registration with email verification
- User Login
- Role-based dashboard (Employer, Employeur, Etudiant, Admin)
- Create, view, and manage job postings
- Apply for jobs
- Accept or reject job applications

## Requirements

- Python 3.x
- `flet` library
- `pyrebase` library

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/khalil135711/flet-authentication-app.git
    ```
2. Navigate to the project directory:
    ```sh
    cd flet-authentication-app
    ```
3. Install the required libraries:
    ```sh
    pip install flet pyrebase
    ```

## Firebase Configuration

1. Create a Firebase project at [Firebase Console](https://console.firebase.google.com/).
2. Obtain your Firebase configuration credentials.
3. Update the `firebaseConfig` dictionary in the code with your Firebase credentials:
    ```python
    firebaseConfig = {
        'apiKey': "YOUR_API_KEY",
        'authDomain': "YOUR_AUTH_DOMAIN",
        'databaseURL': "YOUR_DATABASE_URL",
        'projectId': "YOUR_PROJECT_ID",
        'storageBucket': "YOUR_STORAGE_BUCKET",
        'messagingSenderId': "YOUR_MESSAGING_SENDER_ID",
        'appId': "YOUR_APP_ID"
    }
    ```

## Running the Application

1. Run the application:
    ```sh
    python app.py
    ```
2. Open the application in your browser and start using it.

## Author

KHALIL KADAR - FH Aachen 
