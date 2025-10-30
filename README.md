# DSML-Project-Intrusion Detection System (IDS) using Machine Learning

## Project Objective
This project focuses on the development of an Intrusion Detection System (IDS) using Machine Learning techniques to identify and classify network traffic as normal or malicious, enhancing network security against evolving cyber threats.

## Table of Contents
	•	Project Overview
	•	Features
	•	Dataset
	•	Algorithms Used
	•	Installation
	•	Usage
	•	Results
	•	Conclusion
	•	Future Work
	•	License   		
				
## Project Overview
Intrusion Detection System is a software application that detects network intrusion using various machine learning algorithms. IDS monitors a network or system for malicious activity and protects a computer network from unauthorized access by users, including perhaps insiders. The intrusion detector learning task is to build a predictive model (i.e., a classifier) capable of distinguishing between 'bad connections' (intrusion/attacks) and 'good (normal) connections'.
          
## Features
	•	Preprocessing of real-world IDS datasets
	•	Feature selection and dimensionality reduction
	•	Supervised ML model training and evaluation
	•	Classification of normal vs. attack traffic
	•	Performance metrics: Accuracy, Precision, Recall, F1-Score, ROC-AUC
	•	Visualization of results          
          
## Dataset    
   Download the data set form Kaggle - [**UGRansome dataset**](https://www.kaggle.com/datasets/nkongolo/ugransome-dataset)
**Steps:**
1. Place the dataset in the `data/` folder.  
2. Ensure the notebook paths point to the dataset correctly.
          
## Algorithms Used
	•	Logistic Regression
	•	Decision Tree
	•	Random Forest
	•	K-Nearest Neighbors (KNN)
	•	Support Vector Machine (SVM)	

## Installation
  1. Quick start :  Open Jupyter notebook
  2. Run Directly in Google Colab : [**Open Project in Colab**](https://colab.research.google.com/drive/1Y342cTNSDgIn30RZm7swFb4XcehjIMrf?usp=sharing)

#### Resources Used
- **Editor Used:** Google Colab/ Jupyter notebook
- **Python Version:** 3.12  
- **Platform:** Google Colab  
- **Environment:** Machine Learning - Classification Model

#### Python Packages Used
- **Data Manipulation:** `pandas`, `numpy`  
- **Data Visualization:** `matplotlib`, `seaborn`, `plotly`  
- **Machine Learning:** `scikit-learn`

## Usage
	1.	Place the dataset in the data folder.
	2.	Run the Jupyter notebook: jupyter notebook Main_Project_DSML_Intrusion Detection System Using Machine Learning.ipynb 
	3.	Follow the notebook steps:
		•	Data preprocessing
		•	Feature engineering
		•	Model training
		•	Evaluation and visualization

---

## Results

| Model                | Accuracy | Key Observations |
|----------------------|----------|-----------------|
| Logistic Regression  | 0.744    | Struggles with class 0 (Safe) and class 2 (Suspicious), moderate performance overall. |
| Decision Tree        | 0.994    | Excellent accuracy; almost perfect classification across all classes. |
| **Random Forest**        | **0.993**    | **Similar to Decision Tree; slightly better balanced for class 2. Robust and reliable.** |
| KNN                  | 0.980    | Good performance but slightly lower than tree-based models; sensitive to high-dimensional data. |
| SVM                  | 0.920    | Decent overall, but slower and lower accuracy on class 0. Not ideal for this large dataset. |
- Results vary based on dataset and preprocessing methods.

## Conclusion
The project successfully demonstrates how machine learning can effectively detect cyber threats in network traffic data with high accuracy. The **Random Forest** model achieved approximately **99.3% test accuracy** and provided robust classification across Safe, Alert, and Suspicious traffic classes.

**Classification Report:**
| Class | Precision | Recall | F1-score |   
|-----------------------|-----------|--------|----------|
| Class 0 (Safe)        |   0.99    |  0.99  |   0.99   | 
| Class 1 (Alert)       |   0.99    |  0.99  |   0.99   | 
| Class 2 (Suspicious)  |   0.99    |  1.00  |   0.99   |             

## Future Enhancements
- Implement **advanced feature selection** techniques to reduce dimensionality.  
- Explore **XGBoost** and **LightGBM** models for potentially higher accuracy and faster training.  
- Develop **real-time threat prediction** capabilities for live network traffic.  
- Address **class imbalance** issues in new or evolving datasets.


## License
This project is licensed under the MIT License. See the [MIT License](https://opensource.org/license/mit/) file for details.
