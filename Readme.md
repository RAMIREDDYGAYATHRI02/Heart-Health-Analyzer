# ❤️ Heart Health Analyzer

**Heart Health Analyzer** is a web-based application that predicts the risk of heart disease using Machine Learning and Django.
The system analyzes user health data and provides predictions to help in early detection of heart-related issues.

---

## 🚀 Features

* ❤️ Heart disease prediction using Machine Learning
* 🌐 Web application built with Django
* 📋 Simple and user-friendly input form
* 👨‍⚕️ Doctor and patient data management
* 🗄 Admin dashboard for managing records
* 📊 Accurate analysis based on health parameters

---

## 🛠 Technologies Used

* Python
* Django
* Machine Learning (Scikit-Learn)
* HTML
* CSS
* Bootstrap
* SQLite Database

---

## 📂 Project Structure

```
Heart-Health-Analyzer
│
├── manage.py
├── db.sqlite3
│
├── health_desease
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│   └── asgi.py
│
├── health
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── admin.py
│   └── migrations
│
├── templates
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   └── login_admin.html
│
├── static
│   ├── css
│   ├── js
│   └── images
│
└── media
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/RAMIREDDYGAYATHRI02/Heart-Health-Analyzer.git
```

### 2️⃣ Navigate to the Project Directory

```
cd Heart-Health-Analyzer
```

### 3️⃣ Install Required Packages

```
pip install django
pip install djangorestframework
```

### 4️⃣ Apply Database Migrations

```
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Run the Development Server

```
python manage.py runserver
```

---

## 🌐 Open the Application

Open your browser and go to:

```
http://127.0.0.1:8000/
```

---

## 👤 Admin Panel

Create an admin user:

```
python manage.py createsuperuser
```

Then open:

```
http://127.0.0.1:8000/admin
```

---

## 📊 Input Parameters Used

The prediction model uses the following health parameters:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise Induced Angina
* ST Depression
* Slope
* Number of Major Vessels
* Thalassemia

---

## 🎯 Objective

The goal of this project is to assist in **early detection of heart disease** by analyzing health parameters and providing quick predictions through a web-based system.

---

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit a pull request.

---

## 📜 License

This project is open-source and available under the **MIT License**.
