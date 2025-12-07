# DDoS Detection with Machine Learning

This project detects **Distributed Denial of Service (DDoS) attacks** using machine learning algorithms. By analyzing network traffic patterns, the system can distinguish between **legitimate** and **malicious** traffic, providing proactive defense against DDoS attacks.

--- 

## 🛠️ Technologies & Tools
- Python 3
- scikit-learn (for ML models)
- pandas, numpy (for data processing)

---

## 📂 Project Structure
```text
ddos-detection-ml/
├── README.md
├── icmp_flood_ip_dataset.py
├── run_detection.py
├── train_detection_model.py
├── test_icmp_flood_ip_dataset.csv
├── train_icmp_flood_ip_dataset.csv
├── trained_logistic_model_ip.pkl
└── trained_scaler_ip.pkl
```
---

## 🚀 Getting Started
### Clone the repository
```bash
git clone https://github.com/Mehdi-Ben-Hamou/ddos-detection-ml.git
cd ddos-detection-ml
```
### Train the model
```bash
python train_detection_model.py
```
### Run detection
```bash
python run_detection.py
```
## 📊 Dataset
- train_icmp_flood_ip_dataset.csv: Training data for ICMP flood detection
- test_icmp_flood_ip_dataset.csv: Test data for evaluation

## 💾 Model Files
- trained_logistic_model_ip.pkl: Pre-trained logistic regression model
- trained_scaler_ip.pkl: Scaler used for data normalization

## 🔗 Notes
- The system currently focuses on ICMP flood attacks.
- Additional attack types can be added by extending preprocessing and training scripts.
