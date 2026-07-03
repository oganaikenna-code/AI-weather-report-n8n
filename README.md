# 🌤️ AI Weather Report with n8n

An automated weather reporting workflow built with **n8n**, **JavaScript**, **Google Gemini AI**, and the **Open-Meteo API**.

---

## 📌 Overview

This workflow automatically:

- ⏰ Runs on a schedule
- 🌦️ Retrieves live weather data from the Open-Meteo API
- 💻 Processes the data using JavaScript
- 🤖 Generates a weather summary using AI
- 📧 Sends a professional HTML email through Gmail

---

## 🛠 Technologies Used

- n8n
- JavaScript
- Open-Meteo API
- Google Gemini AI
- Gmail

---

## ⚙️ Workflow

```text
Schedule Trigger
        │
        ▼
HTTP Request
        │
        ▼
Edit Fields
        │
        ▼
JavaScript Code
        │
        ▼
AI Agent
        │
        ▼
Gmail (HTML Email)
```

---

## 📂 Workflow File

Click below to download and import the workflow into n8n.

📥 **[Download the Workflow](./daily-weather-report.json)**

---

## 📷 Screenshots

### HTML Email Output

[![Weather Email](./weather-report-output.png)](./weather-report-output.png)

Click the image above to view it in full size.

---

## 🚀 Future Improvements

- 3-Day Forecast
- Sunrise & Sunset
- Dynamic Weather Icons
- Slack Notifications
- Multi-City Reports

---

## 👨‍💻 Author

**Ogana Ikenna**

Learning AI Automation Engineering one project at a time.
