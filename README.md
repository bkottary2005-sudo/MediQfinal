#  MediQ – Emergency Healthcare Coordination System

> **MediQ** is a unified digital healthcare platform designed to streamline emergency medical coordination by connecting **patients, doctors, hospitals, and healthcare staff** in real time. It helps reduce delays, improve communication, and enable faster decision-making during medical emergencies.

---

##  Table of Contents

- [Overview](#-overview)
- [Problem Statement](#-problem-statement)
- [Proposed Solution](#-proposed-solution)
- [Key Features](#-key-features)
- [Technology Stack](#-technology-stack)
- [Project Structure](#-project-structure)
- [System Workflow](#-system-workflow)
- [Installation Guide](#-installation-guide)
- [Future Enhancements](#-future-enhancements)
- [Contributors](#-contributors)
- [License](#-license)

---

# Overview

Emergency healthcare often suffers from poor communication, delayed information sharing, and inefficient coordination among patients, doctors, ambulance services, and hospitals.

**MediQ** aims to solve this problem by providing a centralized digital platform where emergency cases can be managed efficiently with real-time updates and structured workflows.

The platform enables healthcare providers to respond quickly while keeping all stakeholders connected through a single interface.

---

# Problem Statement

Current emergency healthcare systems face several challenges:

- Patients struggle to locate nearby hospitals.
- Finding an available doctor during emergencies is difficult.
- Communication between hospitals and ambulance services is inefficient.
- Important information is shared through phone calls or handwritten notes.
- Delays in coordination increase response time.
- Lack of centralized emergency management systems.

These issues can lead to delayed treatment and increased risk to patient lives.

---

# Proposed Solution

MediQ introduces a centralized emergency healthcare management platform that enables seamless communication among patients, doctors, hospitals, and medical staff.

The platform provides:

- Instant emergency reporting
- Doctor availability management
- Hospital coordination
- Digital queue management
- Real-time communication
- Faster emergency response

---

#  Key Features

### Emergency Case Reporting

Patients can instantly report medical emergencies through the platform.

---

###  Live Doctor Availability

Doctors can update their availability status in real time.

---

###  Hospital Dashboard

Hospitals receive emergency notifications and manage incoming patients efficiently.

---

###  Appointment & Queue Management

Digital queue management reduces waiting time and improves patient flow.

---

###  Real-Time Notifications

Patients, doctors, and hospital staff receive instant updates.

---

###  Role-Based Dashboards

Separate dashboards for:

- Patient
- Doctor
- Hospital Staff
- Administrator

---

###  Centralized Data Management

All emergency information is stored and managed in one secure platform.

---

### Faster Decision Making

Real-time data sharing helps medical teams make quick and informed decisions.

---

#  Technology Stack

## Frontend

- HTML5
- CSS3
- JavaScript

## Backend

- Node.js
- Express.js

## API

- REST API

## Version Control

- Git
- GitHub

---

#  Project Structure

```
MediQ/
│
├── frontend/
│   └── index.html
│
├── backend/
│   ├── routes/
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── README.md
└── .gitignore
```

---

#  System Workflow

```
Patient
   │
   ▼
Reports Emergency
   │
   ▼
Server (Node.js + Express)
   │
   ├────────► Doctor Dashboard
   │
   ├────────► Hospital Dashboard
   │
   └────────► Staff Dashboard
   │
   ▼
Real-Time Updates
```

---

#  Installation Guide

## Clone the Repository

```bash
git clone https://github.com/bkottary2005-sudo/MediQfinal.git
```

---

## Navigate to Project

```bash
cd MediQfinal
```

---

## Backend Setup

```bash
cd backend
```

Install dependencies

```bash
npm install
```

Run the server

```bash
npm start
```

or

```bash
npm run dev
```

The backend server will start on:

```
http://localhost:5000
```

---

## Frontend Setup

Open

```
frontend/index.html
```

in your browser.

---

# 📸 Screenshots

### Home Page

<img width="2125" height="1071" alt="image" src="https://github.com/user-attachments/assets/86282bd8-efbf-41c8-899e-3bf91b7cef5a" />


---

### Patient Dashboard

<img width="2146" height="1091" alt="image" src="https://github.com/user-attachments/assets/ec81e930-c80b-45ec-9621-801fba0d8209" />


---

### Doctor Dashboard

<img width="2126" height="1060" alt="image" src="https://github.com/user-attachments/assets/239f7398-91fb-4e48-850d-8f328d959ebd" />


---

### Healthcare worker Dashboard

<img width="2205" height="1041" alt="image" src="https://github.com/user-attachments/assets/65b26fd7-7a7b-489c-a7d0-45ec4b3211f4" />

---

#  Future Enhancements

-  Google Maps API Integration
-  Ambulance Live Tracking
-  SMS & Email Notifications
-  Mobile Application
-  AI-based Emergency Priority Prediction
-  Video Consultation
-  Cloud Deployment
-  JWT Authentication
-  Analytics Dashboard
-  Real-time Chat using Socket.io

---

#  Learning Outcomes

This project helped us understand:

- Full Stack Web Development
- REST API Development
- Express.js Routing
- Client-Server Architecture
- Git & GitHub
- Project Structuring
- Backend Development
- Team Collaboration

---

#  Contributors

**Bhoomika K Kottary**

AI & Data Science Student

MS Ramaiah Institute of Technology

---

#  License

This project is developed for educational and academic purposes.

© 2026 Bhoomika K Kottary. All Rights Reserved.

---

#  Support

If you found this project useful,

 Star this repository

Fork it

 Share it with others

---

> **"Technology can save lives when communication is instant." – MediQ**
