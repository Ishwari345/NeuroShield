# 🛡️ NeuroShield – Autonomous Self-Healing Network Intrusion Detection System

An intelligent **Network Intrusion Detection System (IDS)** that combines **Machine Learning, Deep Learning, and Reinforcement Learning** to detect cyber attacks and automatically recommend response actions. NeuroShield uses the **NSL-KDD dataset** and provides an interactive Flask dashboard for real-time network monitoring and self-healing.

![Dashboard Overview](screenshots/dashboard-overview.png)

---

# 📌 Overview

NeuroShield is an AI-powered intrusion detection system designed to improve network security through intelligent threat detection and automated response.

The project analyzes network traffic using the **NSL-KDD dataset**, detects anomalies with **Random Forest**, classifies attacks using an **Artificial Neural Network (ANN)**, and applies **Q-Learning** to recommend autonomous response actions such as **Allow**, **Alert**, or **Block**.

The application integrates these models into an interactive Flask dashboard, enabling users to visualize attacks, monitor predictions, and understand the self-healing process.

---

# ✨ Features

- 🛡️ Intelligent Network Intrusion Detection
- 🌲 Random Forest-based anomaly detection
- 🧠 Deep Neural Network attack classification
- 🤖 Q-Learning autonomous response engine
- 📊 Interactive Flask dashboard
- 📈 Real-time attack prediction
- 🚨 Automated response recommendation (Allow / Alert / Block)
- 📉 Performance metrics and confusion matrix
- 🔒 Self-healing security workflow

---

# 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Flask | Backend Web Framework |
| HTML | Frontend |
| CSS | Styling |
| Bootstrap | Responsive UI |
| Random Forest | Binary Intrusion Detection |
| Artificial Neural Network (ANN) | Multi-class Attack Classification |
| Q-Learning | Autonomous Self-Healing |
| Scikit-learn | Machine Learning |
| TensorFlow / Keras | Deep Learning |
| Pandas | Data Processing |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| NSL-KDD | Network Intrusion Dataset |

---

# 🏗️ System Workflow

```
Network Traffic
        │
        ▼
Feature Extraction
        │
        ▼
Random Forest
(Anomaly Detection)
        │
        ▼
ANN
(Attack Classification)
        │
        ▼
Q-Learning
(Self-Healing Decision)
        │
        ▼
Flask Dashboard
```

---

# 📂 Project Structure

```text
NeuroShield/
│
├── app.py
├── nsl_kdd_loader.py
├── phase1_anomaly_rf.py
├── phase2_dl.py
├── phase3_rl.py
├── models/
├── templates/
├── screenshots/
└── README.md
```

---

# 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/Ishwari345/NeuroShield.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

### Open Browser

```
http://localhost:5000
```

---

# 📷 Project Screenshots

## Dashboard Overview

Shows the complete NeuroShield dashboard with real-time network monitoring and intrusion detection.

![Dashboard Overview](screenshots/dashboard-overview.png)

---

## Random Forest Anomaly Detection

Binary anomaly detection using Random Forest with confusion matrix and performance metrics.

![Random Forest](screenshots/phase1-randomforest.png)

---

## Deep Neural Network Attack Classification

Multi-class attack classification using an Artificial Neural Network with attack distribution visualization.

![Deep Neural Network](screenshots/phase2-classification.png)

---

## Q-Learning Self-Healing Agent

Reinforcement learning dashboard showing the reward matrix, Q-table, and learned policy.

![Q-Learning](screenshots/phase3-qlearning.png)

---

## Live Network Simulation

Real-time visualization of packet flow with automated Allow, Alert, and Block actions.

![Live Network](screenshots/live-network.png)

---

## System Architecture

Overall architecture illustrating the interaction between the Flask application, machine learning models, and autonomous response engine.

![Architecture](screenshots/architecture.png)

---

# 🎯 Applications

- Network Intrusion Detection
- Cybersecurity Research
- Intelligent Threat Analysis
- AI-based Network Defense
- Self-Healing Networks
- Educational AI Project

---

# 🔒 Advantages

- Intelligent attack detection
- Automated response recommendation
- Interactive dashboard
- Hybrid ML + DL + RL architecture
- Easy to extend with new datasets
- Real-time visualization

---

# 🔮 Future Enhancements

- Live packet capture
- Cloud deployment
- User authentication
- Email & SMS alerts
- SIEM integration
- Support for additional IDS datasets
- Real-time network monitoring

---

# 👩‍💻 Author

**Ishwari Bagewadi**

Information Science Engineering Student

---

# 🙏 Acknowledgements

- Scikit-learn
- TensorFlow
- Flask
- Bootstrap
- NSL-KDD Dataset
- Open Source Community
