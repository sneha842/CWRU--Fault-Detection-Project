# CWRU Bearing Fault Detection  

🔹 A Machine Learning project for **bearing fault diagnosis** using the Case Western Reserve University (CWRU) dataset.  
🔹 Goal: Predict machine faults (healthy vs faulty) using vibration signals.  
🔹 Models used: Logistic Regression, Decision Tree, Random Forest, SVM, KNN.  
🔹 Evaluation: ROC Curve, Confusion Matrix, Accuracy, Precision, Recall, F1-score.  

## ⚙️ Tech Stack  
- Python, Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 📊 Results  
- **Logistic Regression** → Accuracy ~ 85%  
- **Decision Tree** → Accuracy ~ 89%  
- **Random Forest** → Accuracy ~ 93% (Best)  
- **SVM** → Accuracy ~ 91%  
- **KNN** → Accuracy ~ 88%  

✅ **Random Forest** gave the most reliable performance for bearing fault detection.  

## 🚀 How to Run  
```bash
git clone https://github.com/sneha842/CWRU--Fault-Detection-Project.git
cd CWRU--Fault-Detection-Project
pip install -r requirements.txt
jupyter notebook
