<div align="center">

# 🦷 AI Dental Appointment Automation

### Intelligent Dental Appointment Booking & Lead Management System

A modern AI-powered dental appointment platform that automates patient enquiries, validates leads, manages appointments, sends confirmation emails, and provides an AI chatbot using **React, TypeScript, n8n, OpenAI, Google Sheets, and Gmail**.

![License](https://img.shields.io/badge/License-MIT-blue.svg)
![React](https://img.shields.io/badge/React-19-61DAFB?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript)
![n8n](https://img.shields.io/badge/n8n-Automation-EA4B71)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT-412991)
![Google Sheets](https://img.shields.io/badge/Google-Sheets-34A853)

</div>

---
<p align="center">
  <img src="./assets/screenshots/UI.png" alt="AI Dental Appointment Automation Banner" width="100%">
</p>

<p align="center">
  <img src="./assets/screenshots/n8n workplace.png" alt="AI Dental Appointment Automation Banner" width="100%">
</p>

---
# 📖 Overview

This project automates the complete dental appointment enquiry process.

Instead of manually handling appointment requests, the system automatically validates patient details, stores enquiries in Google Sheets, generates confirmation emails using AI, and assists patients through an intelligent chatbot.

---

# ✨ Features

- 🦷 Modern Dental Clinic Website
- 📅 Appointment Booking Form
- 🤖 AI Chatbot
- ⚡ n8n Workflow Automation
- 📧 Automatic Email Confirmation
- 📊 Google Sheets Integration
- ✅ Email & Phone Validation
- 🚀 Webhook API Integration
- 📱 Responsive Design
- 🎯 Real-Time Lead Qualification

---

# 🛠 Tech Stack

| Frontend | Automation | AI | Database | Communication |
|-----------|------------|----|-----------|---------------|
| React | n8n | OpenAI | Google Sheets | Gmail |
| TypeScript | Webhooks | GPT | Cloud Storage | Email |
| Tailwind CSS | JavaScript | AI Agent | | |

---

# 📂 Project Structure

```text
AI-Dental-Appointment-Automation
│
├── README.md
├── LICENSE
├── .gitignore
│
├── assets
├── architecture
├── docs
├── prompts
├── screenshots
├── workflow
├── website
├── sample-data
└── templates
```

---

# 🔄 System Workflow

```text
Patient
      │
      ▼
Dental Appointment Website
      │
      ▼
Appointment Form
      │
      ▼
n8n Webhook
      │
      ▼
Lead Validation
      │
      ▼
IF Node
 ├──────────────┐
 │              │
 ▼              ▼
Valid        Fake
Lead         Lead
 │              │
 ▼              ▼
Google      Google
Sheets      Sheets
 │
 ▼
OpenAI
 │
 ▼
Gmail
 │
 ▼
Patient Receives Confirmation Email
```

---

# 🤖 AI Chatbot Flow

```text
Patient

↓

Website Chat Widget

↓

n8n Webhook

↓

AI Agent

↓

OpenAI

↓

Website Response
```

---

# 📋 Appointment Form

The patient provides:

- Full Name
- Email Address
- Phone Number
- Treatment Type
- Preferred Appointment Date
- Notes (Optional)

---

# ✅ Lead Validation

The workflow validates:

- Gmail Email Address
- 10-digit Phone Number

Output:

- Valid Lead
- Fake Lead

Every enquiry is stored along with the validation status.

---

# 📊 Google Sheets Data

Each submission stores:

- Submission Date
- Name
- Email
- Phone Number
- Treatment
- Preferred Date
- Notes
- Email Status
- Phone Status
- Lead Status
- Validation Reason

---

# 📧 Email Automation

After successful validation:

- AI generates a professional HTML email.
- Gmail sends the appointment confirmation.
- Patient receives all submitted appointment details.

---

# 📸 Screenshots

Add screenshots inside the `screenshots/` folder.

- Home Page
- Appointment Form
- Chatbot
- Google Sheets
- n8n Workflow
- Email Confirmation
- Mobile View

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/your-username/AI-Dental-Appointment-Automation.git
```

Go to the project folder

```bash
cd AI-Dental-Appointment-Automation
```

Install dependencies

```bash
npm install
```

Run the development server

```bash
npm run dev
```

---

# ⚙️ Environment Variables

Create a `.env` file.

```env
VITE_WEBHOOK_URL=YOUR_N8N_WEBHOOK_URL
```

---

# 🎯 Future Improvements

- Admin Dashboard
- Patient Portal
- Appointment Rescheduling
- WhatsApp Notifications
- SMS Integration
- Online Payments
- Calendar Booking
- Analytics Dashboard

---

# 👨‍💻 Author

**Vinay Kumar**

AI & Machine Learning Engineer

- GitHub: https://github.com/vinaysingh-05
- LinkedIn: https://www.linkedin.com/in/vinay-kumar080/

---

# ⭐ Support

If you found this project helpful, please consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is licensed under the MIT License.
