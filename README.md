# 🧠 Enhancing the Prediction of DDoS Attacks in IoT Networks Using Context Correlation-Aware Model

### 🎓 Research Project | SRM Institute of Science and Technology, Chennai  
**Authors:** Swati Kumari, Racharla Rakesh Babu, S. Hitesh Borha  
**Guide:** Dr. S. Sathya Priya (Associate Professor, Dept. of CSE)  
**Domain:** Cybersecurity • Machine Learning • Internet of Things (IoT)  
**Date:** May 2024  

---

## 📘 Overview

With the rapid expansion of **Internet of Things (IoT)** devices across critical domains, the risk of **Distributed Denial of Service (DDoS)** attacks has grown exponentially.  
This project introduces a **Context Correlation-Aware Model (CCAM)** that enhances DDoS attack prediction accuracy in IoT environments by leveraging **machine learning and contextual data analysis**.

---

## 🚨 Problem Statement

Existing DDoS detection systems often:
- Struggle to detect evolving and sophisticated attack vectors.
- Generate high false positive rates.
- Lack scalability in heterogeneous IoT networks.

---

## 🎯 Objective

- Develop an **intelligent hybrid detection model** combining **Random Forest** and **Context Correlation Learning Algorithm (CCLA)**.  
- Improve **detection accuracy and adaptability** for real-time IoT security.  
- Reduce **false positives** and enhance **network resilience** against large-scale DDoS threats.

---

## 🧩 Methodology

### 🔹 System Workflow
1. **Data Collection:** Network traffic data from IoT devices and DNS tunneling datasets.  
2. **Preprocessing:** Cleaning, normalization, and feature scaling for balanced input.  
3. **Feature Selection:** Random Forest identifies critical traffic features influencing DDoS behavior.  
4. **Context Correlation Analysis:** Correlates time, source, and destination relationships for multi-source anomaly detection.  
5. **Model Integration:** Combines results from RF and CCLA for more reliable classification.  
6. **Performance Evaluation:** Using metrics like Accuracy, Precision, Recall, and F1-score.

---

## 🏗️ System Architecture

```
[ Data Collection ]
        ↓
[ Data Preprocessing ]
        ↓
[ Feature Selection ]
        ↓
[ Random Forest Classification ]
        ↓
[ Context Correlation Analysis ]
        ↓
[ DDoS Detection Output ]
```

The model learns both **packet-level patterns** and **contextual network behavior**, enabling it to detect even stealthy or zero-day DDoS attacks.

---

## 🧮 Algorithms Used

- **Random Forest (RF):** Ensemble-based learning for high-accuracy classification.  
- **Context Correlation Learning Algorithm (CCLA):** Correlates behavioral data across IoT nodes.  
- **Evaluation Metrics:** Accuracy, F1-Score, Precision, Recall.

---

## 📊 Results

| Algorithm                  | Accuracy | F1-Score | Precision | Recall |
|-----------------------------|-----------|-----------|------------|--------|
| **Random Forest**           | 0.80      | 0.81      | 0.84       | 0.79   |
| Hist Gradient Boosting      | 0.50      | 0.42      | 0.44       | 0.47   |
| AdaBoost                    | 0.51      | 0.45      | 0.47       | 0.49   |
| Gaussian Naive Bayes        | 0.50      | 0.66      | 0.66       | 0.49   |

**✅ Achieved 30% higher accuracy** and **20% reduction in false positives** compared to existing models.

---

## 🧰 Tech Stack

- **Language:** Python  
- **Tools:** Jupyter Notebook, Anaconda, Visual Studio Code  
- **Libraries:**  
  - `scikit-learn` – ML models & metrics  
  - `pandas`, `numpy` – Data handling  
  - `matplotlib`, `seaborn` – Visualization  
  - `tensorflow` – Neural components  

---

## 🧠 Key Contributions

- Introduced **Context Correlation-Aware detection** for improved DDoS prediction.  
- Developed a **hybrid ML model** combining RF and CCLA.  
- Enhanced IoT network security with **scalable and adaptive detection**.  
- Provided an **open-source implementation** for academic and industrial adaptation.

---

## 📚 Research Insights

- Integrates **machine learning** with **behavioral analysis** for holistic detection.  
- Demonstrates that contextual factors (e.g., packet timing & correlation) drastically improve classification.  
- Encourages future research in **Deep Learning-based IoT threat prediction** and **adversarial resilience**.

---

## 🚀 Future Work

- Incorporate **Deep Neural Networks** (CNN, LSTM) for better temporal feature learning.  
- Extend model support for **real-time DDoS mitigation** in IoT-based edge networks.  
- Integrate with **threat intelligence platforms** for proactive defense mechanisms.

---

## 📜 Citation

If you use this work, please cite as:

```
S Hitesh Borha, Swati Kumari, & Rakesh Babu (2024).
Enhancing the Prediction of DDoS Attacks in IoT Networks Using Context Correlation-Aware Model.
SRM Institute of Science and Technology, Chennai.
```

---

## 💡 Acknowledgments

Guided by **Dr. S. Sathya Priya**, Associate Professor, SRM IST  
Special thanks to the **Department of Computer Science and Engineering** for resources and support.

---

## 🧷 Keywords

`Cybersecurity` • `IoT` • `DDoS Detection` • `Machine Learning` • `Random Forest` • `Context Correlation` • `Network Security`
