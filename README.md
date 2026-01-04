# ML Model Resilience to Data Poisoning Attacks in IoT

## 📌 Project Overview
This project analyzes the resilience of classical Machine Learning models against data poisoning attacks in IoT environments. The focus is on evaluating how model performance changes before and after optimization.

The project is based entirely on classical machine learning techniques and does not use deep learning models.

---

## 📂 Dataset
- **Dataset Name:** N-BaIoT (Network-based Detection of IoT Botnet Attacks)
- **Source:** Kaggle  
  https://www.kaggle.com/datasets/mkashifn/nbaiot-dataset
- The dataset is not included in this repository due to its large size.
- Please download the dataset from Kaggle and place it in the project directory before executing the notebook.

---

## ⚙️ Methodology
1. Data loading and initial exploration  
2. Data preprocessing and cleaning  
3. Feature selection to remove irrelevant features  
4. Dimensionality reduction using Principal Component Analysis (PCA)  
5. Training multiple classical machine learning classification models  
6. Introduction and analysis of data poisoning effects on the dataset  
7. Evaluation of misclassification patterns caused by poisoned data  
8. Measurement and analysis of F1-score degradation before and after data poisoning  
9. Baseline vs optimized model performance comparison  
10. Learning curve analysis to study model behavior  
11. Performance evaluation using standard classification metrics   

---

## 🤖 Models Used
- Random Forest Classifier  
- Decision Tree Classifier  
- Logistic Regression  
- K-Nearest Neighbors (KNN)
- XGBoost (XGB)

---

## 📊 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score
- ROC-AUC
- Train time (s) 

---

## ▶️ How to Run
1. Clone this repository to your local machine.  
2. Install the required Python dependencies using the provided `requirements.txt` file.  
3. Download the dataset from Kaggle and place it in the project directory.  
4. Launch Jupyter Notebook and open the project `.ipynb` file.  
5. Execute the notebook cells sequentially to reproduce the results. 

---

## 📄 Project Results
The detailed project report for this work is available at the link below:

🔗 Google Docs Report:  
https://docs.google.com/document/d/1buE8WqAdf61wFu0pSuYavOW3Ui4xl3Iict-Zi9Qlm10/edit

---

## 📄 License
This project is licensed under the MIT License.

---

## 👤 Author
Diksha Gupta
