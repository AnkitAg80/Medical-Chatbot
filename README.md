# Medical-Chatbot
Overview

This is a Medical Chatbot application designed to collect patient information, symptoms, and medical conditions in a secure and multilingual environment. The application supports voice and text input, integrates with external APIs for speech-to-text and text-to-speech, and stores encrypted patient data in MongoDB. It includes a login system for patients and admins, with admins able to view patient reports.

Features
Multilingual Support: Supports languages including English, Hindi, Bengali, Gujarati, Kannada, Malayalam, Marathi, Odia, Punjabi, Tamil, and Telugu.

Voice and Text Input: Patients can provide input via voice or text, with automatic fallback to text after repeated failed voice attempts.

Speech-to-Text and Text-to-Speech: Utilizes Sarvam AI APIs for speech processing.

PDF Report Generation: Generates downloadable patient reports in PDF format, which are auto-deleted after download for security.

Admin Dashboard: Allows admins to view and download patient reports.

No User Data is stored in the device, even the report that is generated gets deleted from the device.


Prerequisites
Python 3.8+
MongoDB Atlas Account: For storing user and patient data.
Sarvam AI API Key: Required for speech-to-text and text-to-speech functionalities. Sign up at Sarvam AI to obtain your API key.
Dependencies: Install the required Python packages listed in requirements.txt.

To run this program, write this in the terminal:
streamlit run main.py

Important Notes:
You need to login to Sarvam Ai to get their API key and then replace it with mine so that it works for you.