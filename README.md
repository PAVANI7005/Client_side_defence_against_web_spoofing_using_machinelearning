# Client_side_defence_against_web_spoofing_using_machinelearning
A browser-based machine learning solution that detects and prevents web spoofing (phishing) attacks in real-time. This project aims to enhance client-side security by analyzing URL patterns and page content through a trained ML model before allowing access, providing an extra layer of protection against phishing websites.
# 🛡️ PhishCatcher — Client-side Defense Against Web Spoofing Attacks Using Machine Learning

PhishCatcher is a web application that protects users against spoofed websites by detecting phishing URLs using machine learning models. Built using Django and integrated with real-time HTML prediction tools, it offers insights into user behavior and threat analytics.

---

## 🚀 Features

- 🔐 User and Service Provider login panels
- 🧠 Predicts phishing or spoofing attacks using trained ML model
- 📊 View spoofing statistics via interactive dashboards
- 📄 Stores user feedback and tracks accuracy
- 🗂 CSV dataset training support

---

## 🧱 Project Structure

phishcatcher/
├── manage.py
├── phishcatcher/ # Django settings & main URLs
├── Remote_User/ # Django app for user-side interface
├── Service_Provider/ # Django app for admin/service analytics
├── Template/
│ ├── htmls/
│ ├── images/
├── Datasets.csv # Dataset used for training ML model


---

## ⚙️ Technologies Used

- 🐍 Python, Django (Web framework)
- 📊 Machine Learning with Scikit-learn / Pandas
- 🧠 Model: URL-based phishing classifier
- 💾 MongoDB or SQLite (default)
- 📈 HTML/CSS/JS for dashboards

---

## 💻 Setup Instructions

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/PhishCatcher.git
   cd PhishCatcher
2.Install dependencies

pip install -r requirements.txt
3.Run Django server

python manage.py runserver
4.Visit in browser

http://127.0.0.1:8000/
📂 Dataset Info
Datasets.csv includes labeled phishing/legit URLs with features like:

1.URL length

2.Presence of @, //, or IP address

3.HTTPS usage

Used for training a decision tree or SVM model for classification.

📜 License
This project is licensed under the MIT License. Free to use, modify, and distribute.


