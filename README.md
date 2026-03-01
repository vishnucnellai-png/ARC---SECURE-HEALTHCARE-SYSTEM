# ARC – Secure Healthcare System

## Overview
MedAccess OS is a secure healthcare access control system demonstrating role-based authentication, multi-factor login (OTP), audit logging, and emergency "break-the-glass" access. Built using HTML, CSS, JavaScript, and Flask, it simulates secure handling of sensitive medical data in a hospital environment for academic purposes.

---

## Problem Statement
Healthcare systems manage highly sensitive patient information. Unauthorized access, lack of accountability, and absence of emergency override mechanisms can compromise patient safety and data privacy.

---

## Proposed Solution
This project implements a secure healthcare platform with:

- Role-Based Access Control (RBAC)
- Multi-Factor Authentication (OTP)
- Emergency Break-the-Glass Access
- Immutable Audit Logging
- Session Timeout & Security Monitoring

---

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Python Flask
- Security: Session Management, OTP Simulation
- Platform: Web Application

---

## Key Features
- Secure Login System with MFA
- Doctor and Admin Role Separation
- Emergency Access with Justification
- Session Expiry Timer
- Login Activity Monitoring
- Audit Trail Logging
- Interactive Dashboard

---

## Project Structure
ARC---SECURE-HEALTHCARE-SYSTEM
│── app.py
│── requirements.txt
│── README.md
│
└── templates
└── index.html

---

## How to Run the Project

1. Clone the repository:
     https://github.com/vishnucnellai-png/ARC---SECURE-HEALTHCARE-SYSTEM
2. Install dependencies:
     pip install -r requirements.txt
3. Run the application:
     python app.py
4. Open your browser and navigate to:
     http://127.0.0.1:5000
   
---

## Future Improvements
- Database Integration
- Biometric Authentication
- Blockchain-based Audit Logs
- Cloud Deployment

---

## Conclusion
This project enhances healthcare data security by combining structured access control, emergency override mechanisms, and transparent logging to ensure safe and accountable medical data access.
