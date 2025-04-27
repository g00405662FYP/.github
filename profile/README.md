# SpamShield

[**Visit SpamShield**](https://spamshield-52b58.web.app/)

SpamShield is a cloud-based spam detection platform designed to help users securely and efficiently identify malicious messages.  
It uses machine learning to classify emails as spam or ham (legitimate). 

## Project Structure

| Repository | Description |
|:---|:---|
| [model](https://github.com/g00405662FYP/SpamShield-Model) | Trained spam detection models (Naive Bayes, Logistic Regression, Random Forest) |
| [backend](https://github.com/g00405662FYP/SpamShield-Backend) | Flask API for classification, authentication, feedback, and Supabase integration |
| [frontend](https://github.com/g00405662FYP/SpamShield-Frontend) | React.js frontend allowing users to upload, classify, and track emails |


## Tech Stack

- **Frontend**: React.js (Firebase Hosting)
- **Backend**: Flask API (Dockerized, deployed on Google Cloud Run)
- **Database**: Supabase (PostgreSQL + Authentication)
- **Authentication**: Supabase Auth (Email/Password verification)
- **Deployment**: Google Cloud, Firebase Hosting


## Features

- User registration and login with email verification
- Upload or manually enter email messages for classification
- Real-time spam/ham classification with confidence scoring
- User feedback system for classification correctness
- View classification history with visual analytics
- Secure API endpoints protected with JWT authentication

## How It Works

1. Users sign up and authenticate securely.
2. Emails are submitted via file upload (.txt, .eml) or manual text input.
3. The Flask backend classifies messages using a trained machine learning model.
4. Results are returned with a "Spam" or "Ham" label and a confidence score.
5. Users can submit feedback if the classification was correct or incorrect.
6. All classification and feedback data is stored in Supabase for further analysis.


## Authentication and Security

- User authentication handled by Supabase Auth.
- API requests secured with JWT authorization headers.
- Frontend stores access tokens securely in localStorage.


## Deployment Summary

- **Backend** deployed using Google Cloud Run
- **Frontend** deployed using Firebase Hosting.
- Supabase handles database hosting, storage, and authentication services.


## Future Improvements

- Dynamic model retraining pipeline using real user feedback


## Acknowledgements

Thanks to my supervisor, Daragh Matthews, for support and guidance throughout this project.
