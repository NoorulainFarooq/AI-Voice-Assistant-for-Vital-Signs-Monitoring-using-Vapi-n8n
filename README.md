# AI-Voice-Assistant-for-Vital-Signs-Monitoring-using-Vapi-n8n
An AI-powered voice assistant that collects patient vital signs through phone calls using Vapi and automates data processing, storage, and alerts using n8n workflows.

 Project Overview:
This project implements an AI-powered voice assistant that interacts with patients over voice calls to collect vital health data such as heart rate, blood pressure, temperature, oxygen level, and symptoms.
The system uses Vapi for real-time voice interaction and n8n for backend workflow automation, data processing, and storage.

It is designed for remote health monitoring, telemedicine, and automated patient checkups.

Objectives:
Automate patient vital sign collection using voice AI
Reduce manual data entry for healthcare staff
Enable real-time data storage and monitoring
Generate alerts for abnormal readings
Provide a scalable workflow-based architecture

 System Architecture:
Patient calls the AI assistant (via Vapi)
AI asks for vital signs (heart rate, BP, temperature, etc.)
Responses are sent to n8n via webhooks

n8n:
Validates the data
Stores it in a database or Google Sheets
Checks for abnormal ranges
Triggers alerts (email/SMS/WhatsApp) if needed
Data can be visualized on a dashboard

 Features:
 Voice-based patient interaction

 Collects vital signs:
Heart Rate
Blood Pressure
Body Temperature
Oxygen Saturation

Symptoms:

Automated workflow using n8n
Stores data in Google Sheets / Database
Alert system for abnormal vitals
Patient identification and history lookup
Secure and structured data handling

Technologies Used:

Vapi – Voice AI agent
n8n – Workflow automation
Google Sheets 

Webhook APIs:
OpenAI / LLM (via Vapi)

Learning Outcomes

Voice AI integration

Workflow automation using n8n

Healthcare data handling

API-based system design

Real-time monitoring logic

Practical AI project for portfolio

 Disclaimer:
This project is for educational and research purposes only.
It is not intended for direct clinical diagnosis or treatment.

Why This Project Matters:
Shows AI + Automation + Healthcare
Demonstrates system design, not just ML
Real-world telehealth application
