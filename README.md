# Electrical-theft-detection-in-power-grids-using-DL-and-RF
This project detects electricity theft in smart grids using Deep Learning and Random Forest algorithms. It analyzes smart meter data to identify abnormal consumption patterns, helping prevent unauthorized usage and reduce energy losses.

# ⚡ Electrical Theft Detection in Power Grids using Deep Learning and Random Forest

## 📌 Overview

This project aims to detect electricity theft in smart power grids by analyzing energy consumption data using Deep Learning and Random Forest models. It identifies unusual usage patterns that may indicate tampering or unauthorized access, ensuring energy security and minimizing losses.

## 💡 Key Features

* Detection of non-technical losses (NTL) using smart meter data
* Hybrid model combining Deep Learning for pattern recognition and Random Forest for classification
* Automated flagging of suspicious consumers for inspection
* Scalable solution for real-time monitoring in smart grid systems

## 🧠 Technologies Used

* Python
* TensorFlow / Keras (for Deep Learning)
* Scikit-learn (for Random Forest)
* Pandas, NumPy, Matplotlib (for data handling and visualization)

## 🗃️ Dataset

* Smart meter data with hourly/daily energy consumption records
* Labels indicating normal vs. theft behavior (if available)
* Data can be synthetically generated or sourced from public smart grid datasets

## 🚀 How to Run

1. Clone the repository
2. Install the required dependencies using `pip install -r requirements.txt`
3. Run the preprocessing script to clean and prepare the data
4. Train and evaluate the hybrid model using `main.py`
5. View flagged theft cases in the output report

## 📊 Output

* Classification accuracy and confusion matrix
* Theft detection report with timestamps and customer IDs

## 📚 Future Enhancements

* Integration with real-time smart meter APIs
* Deployment as a cloud-based service for power utility companies
* Use of Explainable AI (XAI) for interpretability
