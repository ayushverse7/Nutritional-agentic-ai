# 🥗 Nutrition Agentic AI

An AI-powered web application that provides personalized nutrition guidance using the **Groq API** and **Qwen `qwen/qwen3.8-27b`** model.

## ✨ Features

- 👤 Personalized user profiles
- 🥗 Vegetarian & non-vegetarian meal recommendations
- 🍳 Breakfast, lunch & dinner suggestions
- 🥜 Protein & fibre-rich food recommendations
- 💬 AI-powered Nutrition Agent
- 📍 Location-aware food suggestions
- 🛡️ Prompt-injection & safety guardrails
- 🔐 Secure API-key management
- ⚕️ Medical safety disclaimer
- 📱 Responsive and user-friendly interface

## 🧠 AI Architecture

```text
User
  ↓
Web Interface
  ↓
Flask Backend
  ↓
Safety & Guardrails
  ↓
User Profile Context
  ↓
Groq API
  ↓
Qwen qwen/qwen3.8-27b
  ↓
Response Validation
  ↓
Personalized Nutrition Advice
