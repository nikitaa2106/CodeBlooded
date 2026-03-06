SheCare – Menstrual Health Intelligence System

SheCare is a modern health-tech application designed to help women understand, track, and gain meaningful insights about their menstrual health.

Unlike traditional period tracking apps that only record dates, SheCare analyzes cycle patterns, symptoms, mood, and lifestyle factors to generate intelligent insights, detect abnormalities, and provide personalized guidance.

---

Problem Statement

Menstrual health is still a sensitive and often misunderstood topic. Many girls, especially those experiencing their first period, lack reliable guidance and awareness about their cycle patterns, symptoms, and health signals.

Most existing period tracking apps only allow users to log dates. They rarely provide meaningful analysis, health insights, or intelligent assistance.

As a result, users collect data but do not truly understand what it means for their health.

---

Solution

SheCare transforms simple period tracking into an intelligent menstrual health monitoring system.

The system allows users to log:

- Period dates
- Symptoms
- Mood patterns
- Lifestyle factors such as sleep, stress, and exercise

The backend performs pattern analysis on this data to:

- Calculate average cycle length
- Detect irregular menstrual patterns
- Predict upcoming periods and ovulation windows
- Generate a menstrual health score
- Provide personalized insights

An AI-powered assistant built using Qwen2.5 LLM allows users to ask health-related questions and receive contextual guidance based on their cycle data.

---

Key Features

Cycle Tracking

Users can log their period start and end dates and track their menstrual cycle history.

Symptom & Mood Logging

The system allows tracking of:

- Pain levels
- Mood
- Fatigue
- Bloating
- Headache

This helps identify patterns across cycles.

Lifestyle Tracking

Users can log:

- Sleep hours
- Stress levels
- Exercise activity

The system analyzes how lifestyle factors influence cycle health.

Menstrual Health Score

A health score (0–100) is generated based on cycle consistency and symptom trends.

Score ranges:

- 80–100 → Healthy cycle pattern
- 50–79 → Moderate concern
- Below 50 → Needs attention

Pattern Analysis Engine

Backend logic detects patterns such as:

- Irregular cycles
- High pain trends
- Heavy flow patterns
- Lifestyle impact on cycle regularity

Risk Alerts

Users receive alerts when abnormal patterns are detected.

Examples:

- Irregular Cycle Detected
- High Pain Trend
- Heavy Flow Pattern

Cycle Phase Intelligence

The system identifies the user's current cycle phase:

- Menstrual Phase
- Follicular Phase
- Ovulation Phase
- Luteal Phase

Daily insights help users understand energy levels and body changes.

First Period Guide

A beginner-friendly educational guide designed for girls experiencing their first menstruation.

It explains:

- What menstruation is
- What to expect during early cycles
- Hygiene tips
- Emotional changes

Health Report Generation

The system generates a doctor-shareable report including:

- Cycle history
- Symptom trends
- Health score
- Detected alerts

AI Chat Agent

An AI assistant powered by Qwen2.5 LLM provides contextual menstrual health guidance.

Users can ask questions like:

- "Why is my period late?"
- "What helps reduce cramps?"
- "Is my cycle irregular?"

The system injects relevant user cycle data into prompts to generate personalized responses.

---

System Architecture

The application follows a full-stack architecture:

Frontend
Responsive mobile-first health-tech interface

Backend
REST API server handling cycle data, symptom logs, analysis logic, and AI interactions

Database
Stores user profiles, cycle logs, symptom data, mood data, and lifestyle logs

AI Layer
Qwen2.5 LLM integrated for intelligent conversational assistance

---

Tech Stack

Frontend
React / TypeScript (mobile-first responsive UI)

Backend
Node.js
Express.js

Database
MongoDB

AI Model
Qwen2.5 (running locally via Ollama)

Charts & Visualization
Chart libraries for cycle trend visualization

---

Core System Modules

- Authentication System
- Period Tracking System
- Symptom Logging Engine
- Lifestyle Tracking System
- Pattern Analysis Engine
- Risk Alert Detection
- Menstrual Health Score Engine
- Health Report Generator
- AI Chat Agent

---

Running the Project

The entire system is designed to run using a single command for easy setup.

Step 1 – Install dependencies

npm install

Step 2 – Start the system

npm run dev

This command starts:

- Frontend
- Backend API
- Database connection
- AI integration services

---

Future Improvements

- Wearable device integration
- Advanced cycle prediction models
- Multilingual menstrual health assistant
- Doctor consultation integration
- Anonymous research dataset generation for menstrual health studies

---

Impact

SheCare aims to:

- Improve menstrual health awareness
- Provide intelligent cycle insights
- Support first-time menstruating girls
- Encourage data-driven health understanding
- Reduce stigma around menstrual health

By combining data tracking, analytics, and AI assistance, SheCare empowers women to better understand their bodies and take informed health decisions.

---

License

This project was developed for educational and hackathon purposes.
