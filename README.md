# ComplainGo – AI-Powered Road Complaint Assistant

**Jo Dikhe, Bol Do — On-the-Go!**

---

## About This Project

ComplainGo is a concept prototype that reimagines how citizens report road and infrastructure issues in India. It is designed as a scalable model for government services that automates the entire complaint process—from identifying the issue to filling the official complaint form.

The system focuses on **simplicity, accessibility, and speed**, removing common barriers such as complex forms, lack of awareness about complaint platforms, and time-consuming reporting processes. By combining computer vision, large language models, and automation, the project demonstrates how AI can simplify civic participation.

---

## Why This Project?

### The Problem

India records thousands of accidents every year due to infrastructure issues such as potholes, waterlogging, damaged roads, and poor street lighting. However, many of these issues remain unreported due to the following challenges:

**Lack of Awareness**
Many citizens do not know where to file complaints or which official platform should be used.

**Time-Consuming Process**
Online complaint systems often require filling multiple fields and selecting categories, which may take 10–15 minutes.

**Confusing Categories**
Users often struggle to decide the correct category for their complaint.

**Low Digital Literacy**
For elderly or rural users, navigating government portals can be difficult and discouraging.

---

## Our Solution

ComplainGo simplifies the reporting process through an AI-powered assistant.

1. The user captures or uploads a photo of a road issue using their phone.
2. A lightweight image classification model identifies the problem (for example: damaged road, pothole, waterlogging).
3. An LLM automatically generates a structured and formal complaint text.
4. The information is inserted into a complaint form using automation.

This reduces the reporting process from several minutes to **just a few seconds**, enabling citizens to report infrastructure issues quickly and easily.

---
# https://complaingo-team3.streamlit.app/ [Try it Here]

[Screencast from 07-18-2025 04:51:41 PM.webm](https://github.com/user-attachments/assets/3c8b0d52-ac32-47a8-a9d0-f743153c5e79)
## Technical Pipeline

### 1. Frontend Interface

The user interface is built with Streamlit and designed to be mobile friendly.

Features include image upload, webcam capture, and session-based interactions for a smooth experience.

### 2. AI Inference Layer

The system combines computer vision and language models.

A TensorFlow Lite model classifies the road issue from the uploaded image.
A Gemini LLM generates a formal complaint description based on the identified problem using prompt templates.

### 3. Robotic Process Automation

A Selenium automation pipeline interacts with complaint portals and automatically fills the required form fields using the generated information.

### 4. Deployment

The application is deployed using Streamlit Cloud with containerized dependencies and secure API key management.

---

## Team Contributions

ComplainGo was developed as a **collaborative team project** by three contributors.

JUICY – Machine Learning & AI Development
Developed the road-issue image classification model using Teachable Machine and integrated the Gemini LLM for automated complaint generation.

ARNABI DUTTA – Frontend, Automation & Integration
Built the Streamlit user interface, implemented Selenium-based form automation, and handled end-to-end system integration and deployment.

---

## Tech Stack

Frontend
Streamlit with custom CSS

AI Models
Teachable Machine exported to TensorFlow Lite
Gemini Large Language Model

Automation
Selenium with Chromium

Backend and Deployment
Serverless architecture deployed on Streamlit Cloud

Programming Language
Python

Planned Integrations
Firebase, mapping APIs, and government complaint systems

---

## Future Scope

**Automatic Geolocation**
Use GPS metadata or browser geolocation to automatically fill the complaint location.

**Central Issue Database**
Store reports including images, timestamps, and categories for analytics and heatmap visualization.

**Complaint Tracking**
Allow users to track the status of submitted complaints with notifications.

**Smart Route Planning**
Use road-quality data combined with traffic information to recommend safer travel routes.

---

## Contributing

Contributions from developers, designers, and AI enthusiasts are welcome.

Possible areas of contribution include improving the classification model, enhancing UI/UX, and integrating additional government complaint portals.

Steps to contribute:

1. Fork the repository.
2. Create a feature branch.
3. Implement improvements or new features.
4. Submit a pull request with clear documentation.

---

## Vision

ComplainGo demonstrates how **AI, automation, and simple user interfaces** can make civic systems more accessible and efficient. The long-term goal is to create a scalable framework that encourages citizens to actively report infrastructure issues and helps authorities respond more quickly.
