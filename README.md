# PushTrack: Real-time Push-Up Tracker

PushTrack is a real-time push-up tracking application built using Flask, the MoveNet model for pose detection, and Firebase for backend data management. This project offers users the ability to track their push-up repetitions with real-time feedback on form, enhancing their workout experience.

## Features

- **Push-Up Repetition Tracking:** Utilizes the MoveNet model to accurately track push-up repetitions in real-time.
- **Real-time Feedback:** Provides users with instant feedback on their push-up form and repetition count, ensuring accurate workout tracking.
- **Firebase Backend:** Manages backend operations, ensuring data persistence and scalability.
- **User-friendly Interface:** Offers a user-friendly interface built with Flask, enhancing usability and engagement.

## Folder Structure
```
pushtrack/
│
├── app.py               # Main Flask application file
├── config.py            # Configuration file (includes Firebase credentials)
├── requirements.txt     # List of Python dependencies
├── static/              # Static files (CSS, JavaScript, images)
│   ├── css/             # CSS stylesheets
│   ├── js/              # JavaScript files
│   └── img/             # Image files
└── templates/           # HTML templates
    └── index.html       # Main HTML template for the application
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/AsadCodeCraft/PushTrack-Real-time-Push-Up-Tracker.git
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Set up Firebase:
- Create a Firebase project and set up Firestore for backend data storage.
- Obtain Firebase credentials and configure the application.
- Update the Firebase configuration in config.py with your credentials.

### Usage
- Access the application through your web browser.
- Start your push-up session and follow the on-screen instructions.
- Receive real-time feedback on your form and repetition count.
- Track your progress and enjoy an enhanced workout experience!
