# AI-Based Network Intrusion Detection System

## Project Overview
This project implements an **AI-Based Network Intrusion Detection System (NIDS)** using
Machine Learning techniques to identify malicious network activity.

The system uses the **Random Forest algorithm** to classify network traffic as:
- **Benign (Normal traffic)**
- **Malicious (Intrusion / Attack traffic)**

A **Streamlit-based interactive dashboard** is developed to simulate network traffic,
train the model, evaluate performance, and test live traffic behavior.

This project is developed as a **Major Project** for academic evaluation.

---

## Objectives
- To understand how machine learning can be applied to network security
- To detect malicious network traffic using supervised learning
- To visualize model performance using accuracy and confusion matrix
- To simulate real-time traffic analysis through an interactive dashboard

---

##  Technologies Used
- **Programming Language:** Python 3
- **Machine Learning Algorithm:** Random Forest Classifier
- **Libraries:**  
  - pandas  
  - numpy  
  - scikit-learn  
  - seaborn  
  - matplotlib  
- **Dashboard Framework:** Streamlit
- **Platform:** Windows 
- **Development Tool:** VS Code

---

## Project Structure
```
AI-Network-Intrusion-Detection-System/
│
├── nids_main.py
├── README.md
├── screenshots/
│ ├── 01_dashboard.png
│ ├── 02_model_training.png
│ ├── 03_confusion_matrix.png
│ ├── 04_malicious_detection.png
│ └── 05_code_execution.png

```

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```
git clone https://github.com/sathya3103/AI-Network-Intrusion-Detection-System.git

cd AI-Network-Intrusion-Detection-System
```

### 2️⃣ Install Required Libraries
```
pip install pandas numpy scikit-learn streamlit seaborn matplotlib
```

## ▶️ How to Run the Project

Run the Streamlit application using:
```
python -m streamlit run nids_main.py
```

After running the command:
- The application will open in your browser
- URL: `http://localhost:8501`

---

## How the System Works
1. A **synthetic dataset** simulating network traffic is generated
2. Data is split into training and testing sets
3. A **Random Forest model** is trained on the data
4. Performance metrics such as **accuracy** and **confusion matrix** are displayed
5. A **Live Traffic Simulator** allows users to input packet details
6. The system predicts whether the traffic is **Benign** or **Malicious**

---

## Results
- Achieved **high accuracy (~99%)** on simulated network data
- Successfully detected malicious traffic patterns
- Confusion matrix visualizes correct and incorrect classifications
- Real-time prediction works effectively through the dashboard

---

## Screenshots
Screenshots included in this repository show:
- Streamlit dashboard interface
- Model training completion
- Accuracy and confusion matrix
- Live malicious traffic detection
- Code execution in terminal

These screenshots serve as proof of successful implementation.

---

## Security & Ethical Note
- This project uses **simulated network data only**
- No real network packets are captured
- No system-level or administrative access is required

⚠️ This project is strictly for **educational and academic purposes**  
Unauthorized use of intrusion detection techniques on real networks is unethical and illegal.

---


## Author
**E. Sathyanesar**  
B.E. Computer Science Engineering  
GitHub: https://github.com/sathya3103

---

## License
This project is intended for **academic use only**.
