# AI-driven-dynamic-honeypot-system-for-intrusion-detection
Final Year Project

AI-Driven Dynamic Honeypot Intrusion Detection System
📌 Project Overview

The AI-Driven Dynamic Honeypot Intrusion Detection System is a cybersecurity project that integrates a Cowrie SSH Honeypot with Machine Learning techniques to monitor attacker activities and detect malicious behavior. The system captures attacker login attempts, executed commands, and network activities in a controlled environment and analyzes them using machine learning algorithms for intrusion detection.

The project was implemented in a Kali Linux environment using Python, Cowrie Honeypot, and Scikit-learn libraries.

🎯 Objectives

Deploy a Cowrie SSH honeypot in Kali Linux.
Capture attacker login attempts and command activities.
Analyze honeypot-generated logs using machine learning.
Detect malicious activities and dangerous commands.
Compare multiple machine learning algorithms.
Generate attack analysis and intrusion detection reports.

🛠 Technologies Used

Python
Kali Linux
Cowrie Honeypot
Scikit-learn
Pandas
NumPy
Matplotlib
Machine Learning Algorithms

🤖 Machine Learning Models Used

Logistic Regression
Decision Tree
K-Nearest Neighbors (KNN)
Random Forest
Support Vector Machine (SVM)
XGBoost
LightGBM
CatBoost

📊 Best Model Performance

Model	Accuracy
Random Forest	91.73%

The Random Forest model achieved the highest accuracy and was selected as the final intrusion detection model.

🔍 Features of the System

SSH Honeypot Monitoring
Attacker Login Detection
Dangerous Command Detection
Machine Learning-Based Intrusion Detection
Attack Risk Analysis
Command Monitoring
Behavioral Analysis of Attackers
⚠ Dangerous Commands Detected

The system detects suspicious commands such as:

wget
rm
chmod
nc

📂 Project Structure

AI-Driven-Honeypot-IDS/
│
├── dataset/
├── cowrie_logs/
├── model/
├── deploy_ml.py
├── train_model.py
├── requirements.txt
├── screenshots/
└── README.md

🚀 Installation Steps

1️⃣ Clone Repository
git clone <your-github-repo-link>
cd AI-Driven-Honeypot-IDS
2️⃣ Install Requirements
pip install -r requirements.txt
3️⃣ Install Cowrie Honeypot
git clone https://github.com/cowrie/cowrie
cd cowrie
4️⃣ Start Cowrie Honeypot
bin/cowrie start
5️⃣ Run Machine Learning Detection
python3 deploy_ml.py

📈 Results

Successfully deployed Cowrie Honeypot in Kali Linux.
Captured attacker login attempts and command activities.
Trained multiple machine learning models for intrusion detection.
Achieved 91.73% accuracy using Random Forest.
Generated attacker risk analysis and malicious activity detection.

🔮 Future Scope

Real-time machine learning monitoring
Automatic email alerts
Web dashboard integration
Cloud deployment
AI-based threat intelligence
Real-time attack visualization

📚 References

Cowrie Honeypot Documentation
Scikit-learn Documentation
Kali Linux Documentation
Research Papers on Intrusion Detection Systems

👩‍💻 Developed By

Neha G A
Himanchi Kumari M
Chandana Priya C A
Department of Computer Science and Engineering
Nitte Meenakshi Institute of Technology (NMIT)

📌 Note

This project was developed for educational and research purposes in a controlled cybersecurity environment.
