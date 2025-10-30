# DSML-Project-Intrusion Detection System (IDS) using Machine Learning

This project focuses on the development of an Intrusion Detection System (IDS) using Machine Learning techniques to identify and classify network traffic as normal or malicious, enhancing network security against evolving cyber threats.

**Table of Contents**

          •	Project Overview
          •	Features
          •	Datasets
          •	Algorithms Used
          •	Installation
          •	Usage
          •	Results
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
          Download the dataset from Kaggle: [**UGRansome dataset**] (https://www.kaggle.com/datasets/nkongolo/ugransome-dataset)
          
## Algorithms Used
          •	Logistic Regression
          •	Decision Tree
          •	Random Forest
          •	K-Nearest Neighbors (KNN)
          •	Support Vector Machine (SVM)

## Installation
	• Quick start
		- Open Jupyter notebook
 	•  Run Directly in Google Colab
         		- You can execute the entire workflow without any setup: [**Open Project in Colab**] (https://colab.research.google.com/drive/1Y342cTNSDgIn30RZm7swFb4XcehjIMrf?usp=sharing)

#### Resources Used
          - **Editor Used:** Google Colab/ Jupyter notebook
          - **Python Version:** 3.12  
          - **Platform:** Google Colab  
          - **Environment:** Machine Learning/ Classification Model

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

## Results
Performance of the best model (example with Random Forest on UGransomeware):
|Metric|	|Score|
Accuracy	94.2%
Precision	93.5%
Recall	92.8%
F1-Score	93.1%
ROC-AUC	0.96
Results vary based on dataset and preprocessing methods.

## Future Enhancements
	•   Feature selection to reduce dimensionality
	• 	Explore XGBoost / LightGBM for higher accuracy
	• 	Real-time threat prediction on live traffic
	• 	Handle class imbalance in new data

## License
       This project is licensed under the MIT License. See the LICENSE file for details.



	


