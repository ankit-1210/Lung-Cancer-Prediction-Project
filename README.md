

# Lung Cancer Prediction Project 
     The Lung Cancer Prediction Project is a predictive modeling project that uses machine learning algorithms to predict the likelihood of lung cancer based on various input features. The project likely involves data preprocessing, feature engineering, model training, and evaluation to develop an accurate prediction model.


# Problem Statement:

 The objective of this project is to develop a machine learning model to 
predict the likelihood of lung cancer based on a set of given features. Lung 
cancer is one of the leading causes of cancer-related deaths globally, and 
early detection is crucial for effective treatment. By leveraging machine 
learning techniques, we aim to build a predictive model that can assist in 
the early diagnosis of lung cancer, potentially saving lives and improving 
patient outcomes. 

# What We Are Trying to Solve 

The primary goal is to predict whether a person has lung cancer based on 
various attributes related to their lifestyle, medical history, and symptoms. 
The prediction model will use the provided dataset to learn patterns and 
relationships between these attributes and the presence of lung cancer. 
The outcomes of this project can be used to raise awareness and 
encourage timely medical consultations for those at higher risk. 
Dataset Information 
The dataset consists of 309 entries with 16 columns. Each row represents 
an individual, and each column represents a specific feature or attribute of 
the individual. 

# Column Information 
❖ GENDER: Gender of the individual (M: Male, F: Female) 
❖ AGE: Age of the individual 
❖ SMOKING: Smoking status (YES = 2, NO = 1) 
❖ YELLOW_FINGERS: Presence of yellow fingers, a symptom often 
associated with smoking (YES = 2, NO = 1) 
❖ ANXIETY: Presence of anxiety (YES = 2, NO = 1) 
❖ PEER_PRESSURE: Influence of peer pressure (YES = 2, NO = 1) 
❖ CHRONIC_DISEASE: Presence of chronic disease (YES = 2, NO = 1) 
❖ FATIGUE: Presence of fatigue (YES = 2, NO = 1) 
❖ ALLERGY: Presence of allergy (YES = 2, NO = 1) 
❖ WHEEZING: Presence of wheezing (YES = 2, NO = 1) 
❖ ALCOHOL_CONSUMING: Alcohol consumption status (YES = 2, NO = 
1) 
❖ COUGHING: Presence of coughing (YES = 2, NO = 1) 
❖ SHORTNESS_OF_BREATH: Presence of shortness of breath (YES = 2, 
NO = 1) 
❖ SWALLOWING_DIFFICULTY: Presence of difficulty in swallowing (YES 
= 2, NO = 1) 
❖ CHEST_PAIN: Presence of chest pain (YES = 2, NO = 1) 
❖ LUNG_CANCER: Presence of lung cancer (YES, NO) 

# SVM Method in Lung Cancer Prediction Project

The Support Vector Machine (SVM) method is a supervised machine learning algorithm used in the Lung Cancer Prediction Project to classify lung cancer into malignant and benign. SVM works by identifying key samples (support vectors) from all classes and separating them by developing a function that separates them as widely as feasible using these support vectors.

# How SVM Works

An SVM classifier divides a collection of training vectors into two pairs of data points (_x_1, _y_1), (_x_2, _y_2), …(x__m, y__m) where xi∈Rd signifies vectors in a d-dimensional feature space and _y__i_∈{−1, +1} is a class label. The SVM model is created by translating the input vectors onto a new higher dimensional feature space designated as F:R__d_→_H__d′, where d < d′.
