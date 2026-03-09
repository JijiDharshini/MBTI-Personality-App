# 🧠 AI MBTI Personality Lab

**Discover your personality with AI!**  

AI MBTI Personality Lab is a **fun and interactive web app** built with **Streamlit** that predicts your **MBTI personality type** based on what you write about yourself. Explore your traits, play mini-games while waiting, and dive into all 16 MBTI types in an engaging dashboard.  

---

## 🌟 Features

- **🧠 AI Personality Prediction** – Type estimation using a machine learning model  
- **🎴 Clickable MBTI Cards** – Explore all 16 personalities interactively  
- **🎮 Mini-Games** – Small fun games while your personality is analyzed  
- **📊 Trait Visualization** – Bar chart showing personality trait levels  
- **💬 Help Desk** – FAQs and guidance to understand your results  
- **🎯 Confidence Score** – Shows how confident the AI is in its prediction  

---

## 🖼️ Demo Preview

[App Screenshot] : https://drive.google.com/file/d/1O0dEw5vRudAdxzNbq5dGrrRCMerGYXc_/view?usp=drivesdk

> Interactive dark dashboard with clean cards and fun features

---

## 🗂️ Project Structure

MBTI-App/
│
├── app.py                  # Main Streamlit application
├── requirements.txt        # Python dependencies (Streamlit, scikit-learn, pandas, numpy)
├── README.md               # Project overview, instructions, and features
├── .gitignore              # Optional: ignore unnecessary files like __pycache__ or .DS_Store
│
├── Models/                 # Folder containing machine learning models
│   ├── mbti_model.pkl      # Pre-trained MBTI prediction model
│   └── vectorizer.pkl      # TF-IDF vectorizer used to transform input text
│
├── assets/                 # Optional: Images, icons, GIFs, or illustrations
│   └── mbti_logo.png       # Example image for app or README
│
└── utils/                  # Optional: helper scripts or functions
    └── helper_functions.py # Example: text preprocessing or plotting functions
