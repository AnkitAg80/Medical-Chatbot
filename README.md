# Project Title: Medical-Chatbot

## 1. Description / Objective

The objective of this project is to develop a Medical Chatbot application that streamlines the collection of basic patient information prior to doctor consultation. It aims to reduce the time spent on initial screening by automating the gathering of symptoms and medical history, thereby enhancing the efficiency of hospital workflows and improving the overall doctor-patient interaction time.

---

## 2. Features
Multilingual Support: Supports languages including English, Hindi, Bengali, Gujarati, Kannada, Malayalam, Marathi, Odia, Punjabi, Tamil, and Telugu.

Voice and Text Input: Patients can provide input via voice or text, with automatic fallback to text after repeated failed voice attempts.

Speech-to-Text and Text-to-Speech: Utilizes Sarvam AI APIs for speech processing.

PDF Report Generation: Generates downloadable patient reports in PDF format, which are auto-deleted after download for security.

Admin Dashboard: Allows admins to view and download patient reports.

No User Data is stored in the device, even the report that is generated gets deleted from the device.

## 3. Necessary Libraries / Installation Requirements

Install the required libraries by running:

```bash
    pip install streamlit
    pip install ollama
    pip install fpdf
    pip install spacy
    pip install pymongo
    pip install sounddevice
    pip install numpy
    pip install requests
    pip install deep-translator
    pip install streamlit
    pip install pymongo
```
---

## 4. Commands to Run the Project

Copy and paste the following commands into your terminal:

```bash
# Step 1: Clone the repository
git clone https://github.com/AnkitAg80/Medical-Chatbot.git

# Step 2: Navigate into the project directory
cd IIS_PROJECT_GROUP_7

# Step 3: Install dependencies
    pip install streamlit
    pip install ollama
    pip install fpdf
    pip install spacy
    pip install pymongo
    pip install sounddevice
    pip install numpy
    pip install requests
    pip install deep-translator
    pip install streamlit
    pip install pymongo

# Step 4: Run the application
streamlit run main.py
```
---

## 5. File Structure

```
IIS_PROJECT_GROUP_7
│
├── README.md                    
├── main.py                 
├── chatbot.py               
├── Sample_report.pdf       
├── Project_Demo_Video.mp4   
```
---
> **Note:** Ensure Sarvam API key are set properly in your environment for full functionality. You need to login to Sarvam AI to get their API key and then replace it with ours so that it works for you.
