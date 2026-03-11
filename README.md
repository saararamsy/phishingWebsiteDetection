# Phishing Website Detection Using Machine Learning  

## Overview
The project demonstrates building and evaluating machine learning models to classify websites as legitimate or phishing using the PhiUSIIL dataset.  

**Achievement:** High Distinction (HD) awarded for this assignment.

The goal is to explore preprocessing, model training, evaluation metrics (accuracy, precision, recall, ROC/AUC), and feature importance analysis for multiple classification algorithms.  

---

## Dataset
- Source: PhiUSIIL Phishing dataset from UCI ML Repository  
- Attributes: A01–A25 describing website features  
- Target: `Class` (0 = legitimate, 1 = phishing)  
- Subset used: 2,000 observations for reproducibility  

---

## Models Implemented
1. Decision Tree  
2. Naïve Bayes  
3. Bagging (Bootstrap Aggregation)  
4. Boosting (Adaboost)  
5. Random Forest  
6. Artificial Neural Network (ANN)  
7. LightGBM classifier  

Each model is trained on a 70/30 train-test split, with evaluation using confusion matrices, precision, recall, accuracy, and ROC/AUC curves.  

---

## Key Features
- Data preprocessing: missing value handling, factor conversion, train-test split  
- Model evaluation: accuracy, precision, recall, ROC curves, AUC  
- Feature importance analysis for tree-based models (Decision Tree, Random Forest, Bagging, Boosting)  
- Pruned Decision Tree for simplified manual classification  
- Hyperparameter tuning for Random Forest and LightGBM  

---

## Technology Stack
- **Language:** R  
- **Packages:** caret, rpart, e1071, adabag, randomForest, neuralnet, lightgbm, ROCR, dplyr, ggplot2  
- **Tools:** RStudio, R Markdown  
- **Visualization:** ROC curves, boxplots, feature importance graphs  

---

## Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/phishingWebsiteDetection.git
