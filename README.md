# 📉 SignalSleuth – Real-Time Market Anomaly Detector

**SignalSleuth** is a full-stack anomaly detection engine that flags unusual patterns in financial markets — including sharp price movements, volume spikes, or crash signals. It’s designed to help uncover early signs of market instability, manipulation, or sentiment-driven volatility.

> Built as part of my interest in the intersection of finance, machine learning, and real-time systems — this project simulates how hedge funds and risk desks monitor markets for anomalies and black swan events.

---
| **Dashboard** | **Market Trends** | **Prediction Insights** |
|--------------|----------------|----------------|
| ![Dashboard](<signal-sleuth-master/Screenshot 2025-01-12 at 14.31.17.png>) | ![alt text](<signal-sleuth-master/Screenshot 2025-01-12 at 14.31.48.png>)  | ![alt text](<signal-sleuth-master/Screenshot 2025-01-12 at 14.31.27.png>) |

---

---

## 🚀 Features

- 📊 Detects real-time **stock price anomalies** using ML models (Isolation Forest)
- 🔁 Ingests live data for selected stocks
- 📈 Visualizes stock trends with anomalies highlighted
- 📥 Simple and clean UI using **Next.js**
- 🧠 Backend served via **Flask** for running ML-based anomaly predictions
- ☁️ Modular design for easy extension to crypto, news, or social signals

---

## 🛠 Tech Stack

| Layer      | Technology          |
|------------|---------------------|
| Frontend   | Next.js, React, Tailwind CSS |
| Backend    | Flask (Python) + ML Models |
| ML Model   | Isolation Forest (sklearn) |
| Data       | Real-time stock data via API |
| Deployment | (To be integrated: Azure or Vercel) |

---

## 📌 Motivation

In fast-moving markets, sudden price shifts or unusual patterns often precede important events — good or bad. Traditional systems often miss the early signs. This project is an attempt to build a prototype system that catches such signals early, using anomaly detection models backed by live data pipelines.

---

## 📁 Project Structure

```bash
├── backend/
│   └── flask_api/           # ML model logic and anomaly prediction
├── frontend/
│   └── nextjs_app/          # Dashboard UI for viewing anomalies
├── data/                    # Processed time-series data
├── scripts/                 # Utilities for data ingestion
└── README.md
```

---

## 🖼 Demo Preview
 ![](<signal-sleuth-master/Screenshot 2025-01-12 at 14.31.17.png>)

---
## 📈 How It Works
- Stock price and volume data is fetched periodically
- The data is preprocessed and fed into a trained anomaly detection model
- Detected anomalies are returned to the frontend and displayed graphically
- Frontend dashboard shows spikes, dips, and abnormal patterns

---
## 🔮 Future Enhancements (Planned)
- Add sentiment analysis from news or Reddit

- Integrate crypto asset tracking

- Deploy backend on Azure App Services

- Set up CI/CD with GitHub Actions

- Add anomaly explainability using SHAP or LIME

---
## 🚀 About Me
I'm a Master’s student with a strong interest in Software Engineering, FinTech, and Machine Learning. I enjoy building intelligent, data-driven systems and love working at the intersection of code, data, and product thinking.

**Hardik Amarwani**

- Email: [hardikamarwani@gmail.com](mailto:hardikamarwani@gmail.com)
- Github: [github.com/Hard-Hustler](https://github.com/Hard-Hustler)
