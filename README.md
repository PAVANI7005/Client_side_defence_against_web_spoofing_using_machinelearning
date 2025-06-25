# Client_side_defence_against_web_spoofing_using_machinelearning
A browser-based machine learning solution that detects and prevents web spoofing (phishing) attacks in real-time. This project aims to enhance client-side security by analyzing URL patterns and page content through a trained ML model before allowing access, providing an extra layer of protection against phishing websites.
# 🛡️ PhishCatcher — Client-side Defense Against Web Spoofing Attacks Using Machine Learning

PhishCatcher is a web application that protects users against spoofed websites by detecting phishing URLs using machine learning models. Built using  Django and integrated with real-time HTML prediction tools, it offers insights into user behavior and threat analytics.

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

Output:

![Image](https://github.com/user-attachments/assets/fd56e581-ece7-41ee-9c5c-cf3f151c6ea7)

![Image](https://github.com/user-attachments/assets/20d26e8f-2bde-4a07-8840-29a2baab0f6f)

![Image](https://github.com/user-attachments/assets/2fa43f3d-891b-4c62-b1c2-f1635b87e7db)

![Image](https://github.com/user-attachments/assets/33aab22c-9325-4135-8129-d44d8776c3fa)

![Image](https://github.com/user-attachments/assets/b062c39c-68ae-4c04-a32a-f4db705391fc)

![Image](https://github.com/user-attachments/assets/de9355c1-521d-49e4-a507-275517cb9848)

![Image](https://github.com/user-attachments/assets/63fe726f-6ea7-4402-b8fa-1fb45db18621)

![Image](https://github.com/user-attachments/assets/f396b5dd-19e5-446d-a040-3973f73e0504)

![Image](https://github.com/user-attachments/assets/f8ba5d8f-008f-45c2-a0a7-a0051f5769e6)

![Image](https://github.com/user-attachments/assets/9e0a4117-b97c-4489-8284-780c28f05907)

![Image](https://github.com/user-attachments/assets/13a2d1cc-93e5-4437-88cb-011fb90b48bf)

![Image](https://github.com/user-attachments/assets/cb3c40e5-10e6-47ec-8ea9-220abf3c5ece)

![Image](https://github.com/user-attachments/assets/1cb678fa-56d6-4d45-bae7-ebb0cba4f909)
