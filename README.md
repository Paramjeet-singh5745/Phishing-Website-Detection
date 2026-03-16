# 🛡️ Phishing Website Detection System

A **Machine Learning–based web application** that detects whether a website is **Phishing or Legitimate**.
This project helps users analyze URLs and determine potential phishing threats using trained ML models.

🚀 Built with **Python, Flask, Machine Learning, and Web Technologies**.

---

# 📌 Project Overview

Phishing attacks are one of the most common cybersecurity threats where attackers create fake websites to steal sensitive information such as:

* 🔑 Login credentials
* 💳 Credit card information
* 📧 Personal data

This project analyzes a **website URL** and predicts whether it is:

✅ **Legitimate Website**
❌ **Phishing Website**

The prediction is done using a **trained machine learning model**.

---

# ⚙️ Tech Stack

| Technology        | Usage                   |
| ----------------- | ----------------------- |
| 🐍 Python         | Backend logic           |
| 🌐 Flask          | Web framework           |
| 🤖 Scikit-Learn   | Machine learning models |
| 📊 Pandas / NumPy | Data processing         |
| 🎨 HTML + CSS     | Frontend UI             |
| 📁 Pickle (.pkl)  | Saved ML models         |

---

# 📂 Project Structure

```
Phishing-Website-Detection
│
├── Dataset/                     # Dataset used for training
│
├── static/                      # CSS, images, JS files
│
├── templates/                   # HTML templates
│   └── index.html
│
├── app.py                       # Flask application
│
├── phishing.pkl                 # Trained ML model
├── phishing_mnb.pkl             # Multinomial Naive Bayes model
├── vectorizer.pkl               # Feature vectorizer
│
├── Phishing Website Detection System.ipynb   # Model training notebook
│
└── README.md                    # Project documentation
```

---

# 🧠 Machine Learning Model

The system uses **Natural Language Processing and ML algorithms** to detect phishing URLs.

### Algorithms Used

* 🔹 Multinomial Naive Bayes
* 🔹 Feature Vectorization (TF-IDF)

### Workflow

1️⃣ Collect phishing dataset
2️⃣ Preprocess URLs
3️⃣ Convert URLs into numerical features
4️⃣ Train ML model
5️⃣ Save trained model using `.pkl`
6️⃣ Load model in Flask app for predictions

---

# 🖥️ Application Workflow

```
User enters URL
        │
        ▼
Flask Backend
        │
        ▼
Vectorizer converts URL → Features
        │
        ▼
ML Model predicts
        │
        ▼
Result displayed
```

---

# 🚀 How to Run the Project Locally

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/Paramjeet-singh5745/Phishing-Website-Detection.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd Phishing-Website-Detection
```

### 3️⃣ Create Virtual Environment

```bash
python -m venv env
```

Activate environment:

Windows:

```bash
env\Scripts\activate
```

Linux / Mac:

```bash
source env/bin/activate
```

---

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

### 5️⃣ Run the Flask App

```bash
python app.py
```

---

### 6️⃣ Open Browser

```
http://127.0.0.1:5000
```

Enter any website URL and the system will predict if it is **phishing or safe**.

---

# 🎯 Features

✅ Detect phishing websites
✅ Machine learning prediction
✅ Web-based user interface
✅ Fast URL analysis
✅ Cybersecurity focused project

---

# 📊 Dataset

The dataset contains **phishing and legitimate website URLs** used to train the model.

Features include:

* URL structure
* Domain information
* Special characters
* URL length

---

# 🔐 Cybersecurity Importance

Phishing detection helps to:

* Protect user credentials 🔑
* Prevent financial fraud 💳
* Improve internet security 🌐
* Detect malicious websites ⚠️

---

# 📸 Future Improvements

🔹 Deep learning model for better accuracy
🔹 Browser extension integration
🔹 Real-time phishing detection
🔹 API-based detection system
🔹 Advanced UI dashboard

---

# 👨‍💻 Author

**Paramjeet Singh**

Cybersecurity & Software Development Student

GitHub Profile
👉 https://github.com/Paramjeet-singh5745

---

# ⭐ Support

If you like this project:

⭐ Star the repository
🍴 Fork the project
📢 Share with others

---

# 📜 License

This project is open-source and available for learning and research purposes.
