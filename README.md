# Comparative Analysis of Machine Learning and Deep Learning for Air Quality Prediction Using Meteorological and Climate Data

<p align="center">
  <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff"></a>
  <a href="https://www.tensorflow.org/"><img src="https://img.shields.io/badge/TensorFlow-ff8f00?logo=tensorflow&logoColor=white"></a>
  <a href="https://colab.research.google.com/"><img src="https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=fff"></a>
  <a href="https://pandas.pydata.org/"><img src="https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=fff)"></a>
  <a href="https://scikit-learn.org/"><img src="https://img.shields.io/badge/-scikit--learn-%23F7931E?logo=scikit-learn&logoColor=white"></a>
  <a href="https://numpy.org/"><img src="https://img.shields.io/badge/NumPy-4DABCF?logo=numpy&logoColor=fff"></a>
  <a href="https://matplotlib.org/"><img src="https://custom-icon-badges.demolab.com/badge/Matplotlib-71D291?logo=matplotlib&logoColor=fff"></a>
</p>

## :bulb: About
This repository contains the code for our research on air quality predictions using XGBoost, LSTM and Informer using meteorological and climate data. The goal is to compare model performance, model efficiency and feature importance analysis in predicting PM2.5 concentrations across multiple cities.

## :page_with_curl: Paper
The associated paper is available on [IEEE Explore](https://ieeexplore.ieee.org/xpl/conhome/11264842/proceeding) 

## :file_folder: Repository Structure
```
Comparative_Analysis_Of_Machine_Learning_and_Deep_Learning_For_Air_Quality_Prediction
│
├── Dataset and Training File/ # Dataset and scripts (training and testing)
│ ├── General_EDA.ipynb # General EDA on dataset
│ ├── Informer_Model_Training_(Exponential_Smoothing)_Fix (1).ipynb # Informer model training and testing
│ └── LSTM_Preprocessing_Training.ipynb # LSTM model training and testing
│ └── XGBoost_EDA_and_Preprocessing_Training.ipynb # XGBoost mdoel training and testing
│ └── combined_dataset.csv # proccessed dataset
│ └── t_paired_test_For_RMSE_per_city_From_Each_Model.ipynb # t-paired test script 
|
└── README.md # Main project documentation
```

## :computer: Setup
```
1. git clone https://github.com/Andersen-C/Comparative_Analysis_Of_Machine_Learning_and_Deep_Learning_For_Air_Quality_Prediction.git
2. Open the ipynb scripts file in Jupyter Notebook/Google Colab/VS Code
3. Install all the required libraries
4. Run the code
```

## :bar_chart: Results
The results of all models' performance are as follows: 
| Model | RMSE | MAE | R<sup>2</sup> Score | MAPE |
| --- | --- | --- | --- | --- |
| XGBoost | 0.1907 | 0.0939 | **0.9727** | **15.03%** |
| LSTM | 0.0425 | **0.0215** | 0.9203 | 22.86% | 
| Informer | **0.0253** | 0.0441 | 0.9666 | 69.12% | 

## :man: Authors
- **Andersen Chandra** - Lead Researcher 
- **[Laurentius Nicholas](https://github.com/Zeits27)** - Lead Researcher  
- **Dr. Ir. Alexander Agung Santoso Gunawan, M.Si., M.Sc., IPM.** - Supervisor
- **Rilo Chandra Pradana** - Supervisor
