# Career Next

## AI-Based Career Guidance System

Career Next is an AI-based career guidance system designed to help students explore suitable career and education paths based on their individual interests, aptitude, personality, academic background, and future preferences.

The system collects information from students through a quiz and uses AI to generate personalised recommendations, helping them make more informed decisions about their future.

## Features

* Student signup and login
* Interactive quiz to collect student information
* Analysis based on interests, aptitude, personality, and academic preferences
* Personalised career recommendations
* Course and education path suggestions
* AI-powered analysis and guidance
* Firebase integration for storing student data

## Technologies Used

* **Python** – Backend logic and application development
* **Flask** – Building the web application and backend routes
* **Firebase Firestore** – Storing and managing student data
* **Gemini AI** – Generating personalised career recommendations
* **HTML** – Creating the web pages
* **CSS** – Styling the user interface

## How It Works

1. The student creates an account and logs in.
2. The student completes a quiz containing questions related to their interests, aptitude, personality, academics, and future plans.
3. The responses are stored in Firebase Firestore.
4. The Flask backend retrieves and processes the student's information.
5. The data is structured into a prompt and sent to Gemini AI.
6. Gemini analyzes the information and generates personalised career and education recommendations.
7. The recommendations are displayed to the student.

## Project Structure

```text
career-next/
│
├── app.py                 # Main Flask application
├── firebase_setup.py      # Firebase configuration
├── prompt_builder.py      # Builds prompts for AI analysis
├── login.html             # Login page
├── signup.html            # Signup page
├── quiz.html              # Student assessment quiz
├── results.html           # Displays career recommendations
└── style.css              # Application styling
```

## Future Improvements

* Add more detailed career and course recommendations
* Improve the quiz and recommendation logic
* Add college and scholarship suggestions based on location
* Include career trends and job opportunities
* Improve the user interface and overall user experience

## Purpose

The aim of Career Next is to make career guidance more personalised and accessible by combining student inputs with AI-based analysis. Rather than providing the same suggestions to every student, the system is designed to consider multiple factors and provide recommendations that better match an individual's profile.
