# 🔐 Phishing URL Detection System

A Machine Learning–based web application that detects whether a given URL is **safe or phishing**.  
The system analyzes URL-based features and classifies websites in real time using a trained ML model with a Flask web interface.

---

## 📌 Project Overview

Phishing attacks are one of the most common cybersecurity threats. This project helps users identify malicious URLs by analyzing patterns commonly found in phishing websites. The system extracts important URL features and predicts whether the URL is legitimate or phishing.

---

## 🚀 Features

- Real-time phishing URL detection
- Machine Learning–based classification
- Simple and clean Flask web interface
- Feature extraction from URLs
- Easy to run and deploy

---

## 🛠 Tech Stack

- **Python**
- **Scikit-learn**
- **Pandas**
- **Flask**
- **Joblib**
- **HTML (Flask templates)**

---

## 📁 Project Structure

* Phishing-URL-Detection/
│
├── app.py # Flask web application
├── train_model.py # Model training script
├── feature_extraction.py # URL feature extraction
├── phishing.csv # Dataset
├── model.pkl # Trained ML model
├── requirements.txt # Dependencies
├── README.md # Project documentation
├── LICENSE # License file
├── .gitignore # Ignored files
└── screenshots/ # Project screenshots

## 🔍 URL Features Used

- Length of URL  
- Presence of `@` symbol  
- Presence of `-` symbol  
- HTTPS availability  
- Number of dots (`.`)  
- IP address presence in URL  

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

git clone https://github.com/your-username/Phishing-URL-Detection.git

cd Phishing-URL-Detection

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Train the Machine Learning Model

python train_model.py


4️⃣ Run the Flask Application

python app.py

5️⃣ Open in Browser

http://127.0.0.1:5000

🎯 Use Cases

Cybersecurity learning projects

Academic mini projects

GitHub portfolio enhancement

Beginner ML + Flask practice

Interview demonstrations

🔮 Future Enhancements

Improve accuracy with larger datasets

Add deep learning models

Deploy on cloud (AWS / Render / Railway)

Browser extension support

API-based phishing detection

👨‍💻 Author

Vishaal S
B.E Computer Science & Engineering (AIML)
Interested in Cyber Security & Machine Learning
