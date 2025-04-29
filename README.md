An Intelligent Two-Layer Intrusion Detection System for the Internet of Things
🔐 Overview
This repository contains the code and resources for my project: An Intelligent Two-Layer Intrusion Detection System (IDS) for the Internet of Things (IoT). The project proposes a novel two-layered architecture that enhances security in IoT environments by detecting and classifying malicious traffic using a combination of machine learning and deep learning techniques.

🧠 Key Features
Two-Layer IDS Architecture

Layer 1: Anomaly detection using supervised machine learning models.

Layer 2: Attack classification using deep learning models for finer granularity.

IoT-Focused Dataset: Trained and evaluated on a dataset tailored for IoT network traffic.

Model Training and Evaluation Scripts: Includes code for preprocessing, model training, testing, and performance evaluation.

Modular and Scalable Design: Easy to extend with additional algorithms or datasets.


🚀 How to Run
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/intelligent-iot-ids.git
cd intelligent-iot-ids
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Prepare the dataset

Place your dataset in the data/ directory.

Run preprocessing scripts as needed.

Run the IDS

bash
Copy
Edit
python main.py
🧪 Models and Techniques Used
Layer 1 (Anomaly Detection):

Algorithms: Random Forest, SVM, Decision Tree, etc.

Layer 2 (Attack Classification):

Algorithms: CNN, LSTM, or hybrid DL models.

Evaluation Metrics: Accuracy, Precision, Recall, F1-Score, Confusion Matrix

📊 Results
The two-layer system significantly improves detection accuracy while minimizing false positives compared to single-layer approaches. Detailed performance metrics and comparison charts are available in the results/ directory.

📚 References
CICIDS 2018 Dataset

Research papers on IDS in IoT and machine learning applications in cybersecurity.



