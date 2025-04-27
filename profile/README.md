# 📬 SpamShield

## 🚀 Tech Stack

- **Frontend**: React.js (Firebase Hosting)
- **Backend**: Flask API (Dockerized, deployed on Google Cloud Run)
- **Database**: Supabase (PostgreSQL + Authentication)
- **Authentication**: Supabase Auth (Email/Password verification)
- **Deployment**: Google Cloud, Firebase Hosting

## 🛡️ Features

- User registration and login with email verification
- Upload or manually enter email messages for classification
- Real-time spam/ham classification with confidence scoring
- User feedback system for classification correctness
- View classification history with visual analytics
- Secure API endpoints protected with JWT authentication

## 🧠 How It Works

1. Users sign up and authenticate securely.
2. Emails are submitted via file upload (.txt, .eml) or manual text input.
3. The Flask backend classifies messages using a trained machine learning model.
4. Results are returned with a "Spam" or "Ham" label and a confidence score.
5. Users can submit feedback if the classification was correct or incorrect.
6. All classification and feedback data is stored in Supabase for further analysis.

## 🎯 Goals

- Provide a secure, fast, and user-friendly spam detection platform.
- Allow real-time user feedback to help improve model accuracy over time.
- Showcase full-stack cloud deployment using modern DevOps practice.

## 📚 More Information

SpamShield was developed as part of a final-year software engineering dissertation project.  
The system emphasizes modern architecture, real-world hosting solutions, and user-centered design.

