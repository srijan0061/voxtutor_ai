# 🎓 VoxTutor AI

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-black?style=for-the-badge&logo=flask">
  <img src="https://img.shields.io/badge/MySQL-Database-orange?style=for-the-badge&logo=mysql">
  <img src="https://img.shields.io/badge/Google-Gemini%20AI-blue?style=for-the-badge&logo=google">
  <img src="https://img.shields.io/badge/Razorpay-Payment%20Gateway-0C7BFF?style=for-the-badge">
</p>

<p align="center">
An AI-powered viva preparation platform built with Flask that helps students practice mock viva sessions, improve interview confidence, and track learning progress using Google Gemini AI.
</p>

---

# 📖 Overview

**VoxTutor AI** is a modern AI-powered web application designed to help university students prepare for viva examinations through intelligent mock interviews, subject-based quizzes, adaptive AI questioning, and performance analytics.

The platform combines Artificial Intelligence, authentication, payment integration, and analytics into one complete learning solution.

---

# ✨ Features

## 🤖 AI-Powered Viva Practice

- AI-generated viva questions using Google Gemini
- Adaptive follow-up questions
- Interactive mock interview sessions
- AI coaching responses
- Subject-wise question generation

---

## 📚 Subject-Based Practice

Supports multiple technical subjects including:

- Database Management System (DBMS)
- Operating System (OS)
- Data Structures
- Computer Networks
- Artificial Intelligence
- Software Engineering

---

## 📝 Quiz System

- Subject-based quizzes
- Performance evaluation
- Session history
- Practice recommendations

---

## 📊 Student Dashboard

Users can:

- View recent viva sessions
- Track performance
- Monitor learning progress
- Review previous attempts
- Access personalized recommendations

---

## 🔐 Authentication

Supports:

- Email & Password Login
- User Registration
- Google OAuth Login

---

## 💳 Subscription & Payments

Integrated with **Razorpay** for secure online payments.

Features include:

- Premium subscription plans
- Payment verification
- Order management
- Invoice generation

---

## 📧 Email Invoice System

After successful payment:

- PDF Invoice is generated
- Invoice is emailed automatically
- Purchase history is maintained

---

## 🗄 Database Management

MySQL is used for storing:

- User accounts
- Subscription plans
- Orders
- Viva session history
- Quiz results

---

# 🏗 Project Architecture

```
                +----------------------+
                |      User Browser    |
                +----------+-----------+
                           |
                           |
                     Flask Web Server
                           |
        ---------------------------------------
        |             |            |          |
        |             |            |          |
     MySQL       Google AI     Razorpay   Flask-Mail
   Database       (Gemini)      Payment      Email
```

---

# 🛠 Tech Stack

| Category | Technology |
|-----------|------------|
| Backend | Flask |
| Language | Python |
| Database | MySQL |
| Authentication | Flask Login + Google OAuth |
| AI | Google Gemini AI |
| Payment | Razorpay |
| Email | Flask-Mail |
| PDF Generation | pdfkit |
| Frontend | HTML, CSS, JavaScript |
| Templates | Jinja2 |
| Environment | python-dotenv |

---

# 📂 Project Structure

```
VoxTutor-AI/
│
├── static/
│   ├── css/
│   ├── js/
│   ├── images/
│
├── templates/
│   ├── home.html
│   ├── login.html
│   ├── signup.html
│   ├── dashboard.html
│   ├── practice.html
│   ├── quiz.html
│   ├── pricing.html
│   └── ...
│
├── app.py
├── config.py
├── requirements.txt
├── .env
└── README.md
```

---

# 🚀 Installation

## 1. Clone the Repository

```bash
git clone https://github.com/yourusername/VoxTutor-AI.git

cd VoxTutor-AI
```

---

## 2. Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4. Configure Environment Variables

Create a `.env` file.

Example:

```env
SECRET_KEY=your_secret_key

MYSQL_HOST=localhost
MYSQL_USER=root
MYSQL_PASSWORD=password
MYSQL_DB=voxtutor

GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_CLIENT_SECRET=your_google_client_secret

GEMINI_API_KEY=your_gemini_api_key

RAZORPAY_KEY_ID=your_key
RAZORPAY_KEY_SECRET=your_secret

MAIL_SERVER=smtp.gmail.com
MAIL_PORT=587
MAIL_USERNAME=example@gmail.com
MAIL_PASSWORD=your_password
```

---

## 5. Run the Application

```bash
python app.py
```

Open:

```
http://127.0.0.1:5000
```

---

# 💡 Core Functionalities

- AI Viva Practice
- Subject-wise Mock Interviews
- Google OAuth Authentication
- Email Login & Registration
- Razorpay Payment Gateway
- Student Dashboard
- Quiz Sessions
- Performance Tracking
- Session History
- Invoice PDF Generation
- Email Notifications
- MySQL Data Storage

---

# 🔒 Authentication Flow

```
User

↓

Login / Google OAuth

↓

Authentication

↓

Dashboard

↓

Practice / Quiz

↓

Performance Stored

↓

Analytics Updated
```

---

# 💳 Payment Flow

```
Select Plan

↓

Checkout

↓

Razorpay Payment

↓

Payment Verification

↓

Database Update

↓

Invoice Generated

↓

Invoice Emailed
```

---

# 🤖 AI Workflow

```
Student asks question

↓

Google Gemini API

↓

AI generates response

↓

Adaptive follow-up question

↓

Performance recorded
```

---

# 📈 Future Enhancements

- 🎤 Real-time voice recognition
- 🔊 Speech-to-text viva sessions
- 📱 Mobile responsive PWA
- 🏆 Leaderboards
- 📄 Downloadable performance reports
- 🌙 Dark mode
- 👨‍🏫 Faculty/Admin dashboard
- 📹 Video interview simulation
- 📊 Advanced analytics
- 🔔 Smart study reminders

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Srijan Pandit**

MCA Student | Full Stack Developer | AI Enthusiast

- GitHub: https://github.com/srijan0061
---

# ⭐ Support

If you found this project helpful:

⭐ Star the repository

🍴 Fork the project

🐛 Report issues

💡 Suggest new features

---

<p align="center">
Built with using Flask, Google Gemini AI, MySQL & Razorpay.
</p>
