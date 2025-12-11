# 🚗 Impaired Driving Detection Using Multi-Modal Sensor Data  
### *Capstone Project | Machine Learning • Behavioral Analytics • Biosignals • Power BI*

This project builds a machine learning system to detect impaired driving using **physiological, behavioral, and performance indicators** collected from a controlled driving simulator study at Oakland University.

---

## 🎯 Objective
To identify **quantifiable behavioral and physiological markers** that signal early impairment and develop ML models capable of detecting high-risk driving states.

---

## 📊 Data Sources

### ✔ BAC (Breathalyzer)
### ✔ ECG (BITalino biosensor)
### ✔ KSS (Karolinska Sleepiness Scale)
### ✔ Simulator performance:
- Speed  
- Speed variability  
- Steering variability  
- Lane deviation  
- Reaction time  

Dataset size: **1,000+ time-synced multi-sensor observations**

---

## 🧠 Methods Used

### **1. Preprocessing**
- Missing data handling  
- Sliding window + signal segmentation  
- Noise filtering of ECG  
- Z-score normalization  
- Outlier cleaning  

### **2. Feature Engineering**
- HRV features from ECG  
- Speed variance, steering variance  
- DMS visual cues  
- BAC brackets  
- Sleepiness classification  

### **3. Machine Learning Models**
- Logistic Regression  
- Random Forest  
- Decision Tree  
- (Optional add) XGBoost  
- PCA for dimensionality reduction  

---

## 📈 Key Findings

- **Steering variability** is one of the most sensitive indicators of early impairment  
- **BAC strongly correlates** with impaired driving performance  
- **Sleepiness (KSS)** rises with increased variability in physiological signals  
- ML models achieved **high F1-scores**, correctly identifying high-risk states  
- Physiological + behavioral features combined > single-modality models  

---

## 📊 Dashboard Insights (Power BI)

- Overall impairment levels  
- Speed & steering changes  
- Drowsiness patterns  
- BAC distribution and correlation  
- Individual driver performance breakdowns  

(Screenshots included in `/dashboards`)

---

## 📁 Repository Structure
data/
notebooks/
dashboards/
scripts/
reports/
images/

---

## 🚀 Future Work
- Real-time in-vehicle impairment detection  
- Deep learning models for time-series ECG  
- DMS (camera) based multimodal fusion  
- Larger participant diversity  

---

## 🛠 Tools & Technologies
Python • Pandas • Scikit-Learn • NumPy • Matplotlib  
BITalino ECG • Power BI • Excel • Jupyter Notebook

---

## 👩‍💻 Author
**Vishaka Sharma**  
Business Analytics | Data Science  

