# AI Room Booking Chatbot

An AI-powered chatbot built using **IBM Watson Assistant** that allows users to book meeting rooms through a conversational interface. The chatbot collects booking details and sends room booking requests via email using **IBM Cloud Functions**.

---

## 🚀 Features

- Conversational room booking
- IBM Watson Assistant integration
- Automated email notifications
- IBM Cloud Functions support
- Simple and user-friendly interface

---

## 🛠️ Tech Stack

- IBM Watson Assistant
- IBM Cloud Functions
- Python
- JSON
- Gmail SMTP

---

## 📂 Project Structure

```
AI-Room-Booking-Chatbot/
│── skill-Room-Booking.json
│── IBM_Cloud_Function.py
│── demo.gif
└── README.md
```

---

## ⚙️ Setup

1. Clone this repository.

```bash
git clone <repository-url>
cd AI-Room-Booking-Chatbot
```

2. Create an IBM Cloud account.

3. Provision an **IBM Watson Assistant** service.

4. Create a new assistant and import the provided `skill-Room-Booking.json` file.

5. Create an **IBM Cloud Function** using Python runtime.

6. Copy the code from `IBM_Cloud_Function.py` into the cloud function.

7. Generate a Gmail App Password and update it in the Python file.

8. Enable the Cloud Function as a Web Action and copy its URL.

9. Configure the Webhook URL in IBM Watson Assistant.

10. Test the chatbot by submitting a room booking request.

---

## 📧 Workflow

```
User
   │
   ▼
IBM Watson Assistant
   │
   ▼
IBM Cloud Function
   │
   ▼
Gmail SMTP
   │
   ▼
Booking Confirmation Email
```

---

## 📄 License

This project is intended for educational and learning purposes.

## Project Snapshot
This project was prepared for the December 2025 repository history update.

