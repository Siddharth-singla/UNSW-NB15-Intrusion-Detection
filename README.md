# Network Intrusion Detection using UNSW-NB15 Dataset

## Project Overview

This project builds a **Machine Learning based Intrusion Detection System (IDS)** using the UNSW-NB15 cybersecurity dataset.

The system analyzes network traffic features to classify whether the traffic is **normal or malicious**, helping detect cyber attacks.

---

## Dataset

The dataset used is **UNSW-NB15**, a modern network intrusion dataset containing various simulated attack types.

Files included:

* UNSW_NB15_training-set.parquet
* UNSW_NB15_testing-set.parquet

The dataset contains features such as:

* packet size
* protocol
* service
* duration
* source bytes
* destination bytes
* attack category

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

Parquet files are loaded using Pandas.

### 2. Data Preprocessing

* Handling missing values
* Encoding categorical features
* Feature selection

### 3. Exploratory Data Analysis

Visualization of network traffic patterns and attack distributions.

### 4. Model Training

Machine learning models trained to classify network traffic.

### 5. Model Evaluation

Evaluation performed using metrics such as:

* Accuracy
* Confusion Matrix
* Precision and Recall

---

## Applications

Intrusion detection systems help protect:

* enterprise networks
* cloud infrastructure
* financial systems
* government networks

---

## Future Improvements

* Deep learning based intrusion detection
* Real-time detection pipeline
* Deployment with Flask or FastAPI
* Integration with security dashboards

---

## Author

Siddharth Singla
Computer Science Student | AI/ML Enthusiast
