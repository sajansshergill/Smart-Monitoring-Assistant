# Smart-Monitoring-Assistant

---

## 🎯 Objective:
Develop a Python-based assistant to detect anomalies in manufacturing IT systems (e.g., privilege abuse, malware behavior, or unauthorized access) using log data and time-series analytics.

---

## 🔧 Key Steps & Modules
1. Data Ingestion
- Source: Simulated or real system logs (e.g., syslog, access logs, performance metrics)
- Tools: pandas, glob, os

2. Preprocessing & Feature Engineering
- Timestamp parsing, sorting
- Extracting metrics: CPU, memory, user activity, etc.
- Handling missing values, log levels

3. Anomaly Detection Models
- choose 1–2 of these:
  
  i. Isolation Forest (unsupervised, robust to noise)
  ii. Prophet (trend & seasonality-aware)
  iii. LSTM (for sequence anomaly modeling, optional for advanced)

4. Alerting System
- Send alerts via:
  
  i. Slack webhook (using requests)
  ii. or Email (via smtplib or yagmail)

5. Dashboard & Visualization
- Real-time or batch plots using:
  i. matplotlib, seaborn, plotly
  ii. Metrics: anomaly scores, thresholds, time of event

6. Documentation
- Markdown-style .md logs for dev/test cycles
- Optional: export charts to PDF or HTML report
