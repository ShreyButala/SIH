# 🤖 Arogyam Mitra: Your AI-Driven Public Health Companion 🇮🇳

## Bridging the Health Information Gap via AI, WhatsApp, and SMS.


-----

## 🌟 The Vision: Why Arogyam Mitra?

### The Challenge

Millions in **rural and semi-urban areas** lack immediate, trustworthy access to essential health information. This gap causes delays in treatment, promotes misinformation (like vaccine hesitancy), and slows our response to local disease outbreaks.

### Our Solution

**Arogyam Mitra** (Health Friend) is a **24/7 AI Chatbot** designed to solve this. We use the most accessible communication tools—**WhatsApp and SMS**—to deliver verified, multilingual health guidance directly to the user's phone, empowering them to make better, faster health decisions.

-----

## ✨ Core Features: Health at Your Fingertips

Arogyam Mitra is designed for **maximum accessibility** and **comprehensive support**.

| Feature | Description | Accessibility Focus |
| :--- | :--- | :--- |
| **🗣️ Multilingual Support** | Instant answers in **local languages** including **Odia, English, Hindi, and Gujarati**. | Broad reach across different states. |
| **🤒 Symptoms Analyzer** | Describe your symptoms (e.g., fever, cough), and the AI will offer **reliable, preliminary guidance** and next steps. | Immediate help without needing a clinic visit. |
| **💉 Vaccination Services** | Get **personalized reminders** and complete, age-appropriate schedules (e.g., Newborn, 6 Months, 5 Years). | Crucial for improving immunization rates. |
| **🚨 Real-Time Alerts** | Receive immediate updates on **local disease outbreaks** (like Dengue) and important government health advisories. | Critical for community-wide prevention. |
| **🏡 Preventive Care** | Provides simple, practical **Homemade Health Tips** and daily hygiene advice (e.g., drinking clean water, washing hands). | Focus on wellness and prevention, not just sickness. |
| **📍 Nearby Care** | Locates and provides directions to the **Nearest Hospital or Health Center**. | Fast access during emergencies. |
| **🧑‍⚕️ Talk to a Health Worker** | Option to connect directly with a **local health worker** via WhatsApp or phone for personalized human intervention. | Ensures human oversight when AI guidance isn't enough. |

-----

## 🧠 Technology & Architecture

Our platform is built for resilience, scalability, and secure data handling, even in low-resource network areas.

### The Brain: Technical Stack

| Area | Key Technologies | Why we chose it |
| :--- | :--- | :--- |
| **Conversational AI** | **Rasa** & **Google Dialogflow** | Open-source flexibility (Rasa) and enterprise-grade reliability (Dialogflow) for complex dialogue management and LLM fine-tuning. |
| **Messaging Integration** | **WhatsApp Business API** & Python/JS | Connects the AI logic directly to the user's preferred communication channels. |
| **Multilingual Engine** | Based on **AI4Bharat** principles | Ensures accurate understanding and generation of responses in low-resource Indian languages. |
| **Data & Security** | **Secure & Private User Data Storage** | Strict **HIP-Compliant** framework with consent-based data management. |

### Architecture Flow

1.  **User Interface (WhatsApp/SMS):** Accepts **multilingual Text or Voice** input.
2.  **Voice-to-Text (V-T-T):** Converts voice commands into text.
3.  **NLP Engine:** Processes the text, understands user intent, and manages the conversation flow.
4.  **API Integration Layer:** Pings **Government Health Databases** (for verified data) and **Real-Time Alert Systems**.
5.  **Text-to-Speech (TTS):** Converts the final answer back to voice for users who prefer listening.
6.  **Response:** Delivers the verified, timely information back to the user 24/7.

-----

## 📈 Impact and Benefits

We are striving for a **Net Positive Health Outcome** across the entire community ecosystem.

### Expected Outcomes

  * Achieve **80% Accuracy** in all health queries processed.
  * See a **20% Increase** in general health awareness and early detection practices.
  * Overall **Improved Public Health Metrics** at the regional level.

### Benefits for All Stakeholders

| Community | Healthcare System | Government & Policy Makers |
| :--- | :--- | :--- |
| **Easy, Trusted Access:** Reliable information 24/7. | **Reduced Patient Load:** Efficiently triage basic queries, freeing up staff. | **Data-Driven Decisions:** Real-time data on emerging symptoms and queries. |
| **Better Adherence:** Improved vaccine coverage and awareness of preventive care. | **Efficient Disease Surveillance:** Real-time monitoring for faster outbreak response. | **Better Crisis Response:** Ability to send targeted, mass alerts instantly. |

-----

## 💻 Prototype Overview (sih.html)

The included `sih.html` file is a fully functional web prototype that demonstrates the platform's core functionalities:

1.  **Chat Interface:** A mockup of the WhatsApp chat, showing the **language selector** (English, Hindi, Odia, Gujarati) and easy-to-tap buttons for **Symptoms, Vaccination, and Emergency**.
2.  **Health Worker Dashboard:** A separate view for local healthcare staff, featuring data visualizations using Chart.js to track **User Queries Over Time** and a table for the **Latest Vaccination Schedules**.
3.  **Forms:** Simple forms for users to **report symptoms** and sign up for **SMS Vaccination Reminders**, confirming the planned data input mechanisms.
4.  **Emergency Helpline:** A dedicated section listing crucial Pan-India SOS numbers (112, 108, 104, 14416 - Tele-MANAS).

-----

## 🛠️ Getting Started (SIH Context)

This project was developed for the Smart India Hackathon.

| Detail | Value |
| :--- | :--- |
| **Event** | Smart India Hackathon 2025 |
| **Problem Statement ID** | 25049 |
| **PS Category** | Software |
| **Team Name** | TechTide |
| **GitHub Repository** | [GitHub - ShreyButala/SIH](https://www.google.com/search?q=https://github.com/ShreyButala/SIH) |

### Local Setup

To view the static web prototype:

1.  Download or clone the repository.
2.  Open the `sih.html` file directly in your web browser. (No server needed, as it uses local files and CDN resources like Tailwind CSS and Chart.js).
