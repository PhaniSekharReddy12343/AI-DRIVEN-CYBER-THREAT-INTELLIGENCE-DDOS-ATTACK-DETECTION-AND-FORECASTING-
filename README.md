DDoS Attack Detection and Forecasting

This project focuses on detecting and forecasting Distributed Denial of Service (DDoS) attacks using supervised machine learning techniques. It analyzes network traffic data and classifies it as either **Benign** or **DDoS** using models like Random Forest, Logistic Regression, and Neural Networks.

## Features

- Data preprocessing and exploratory data analysis (EDA)
- Feature selection using Random Forest importance
- Model training and evaluation:
  - Random Forest
  - Logistic Regression
  - Neural Network (MLPClassifier)
- Performance visualization (confusion matrix, ROC curves)
- ROC-AUC comparison across models

## Dataset

The dataset used in this project is `ddos_dataset.csv`, which includes labeled network traffic features. Labels indicate whether the traffic is benign or malicious (DDoS).

## Dependencies

Install the following Python libraries before running the project:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## How to Run

1. Clone the repository
2. Place `ddos_dataset.csv` in the working directory
3. Run the Jupyter notebook or Python script (`.ipynb` or `.py`) to execute the pipeline

## Model Evaluation Metrics

- **Accuracy**
- **F1-Score**
- **Precision**
- **Recall**
- **Confusion Matrix**
- **ROC Curve and AUC**

## Results Summary
| Model              | Accuracy | F1 Score | Precision |
|-------------------|----------|----------|-----------|
| Random Forest      | 99.71   | 99.84    | 99.78     | 
| Logistic Regression| 94.89   | 97.22    | 95.24     | 
| Neural Network     | 92.85   | 96.15    | 93.40     | 


## Visualizations

- Pie chart and bar chart for label distribution
- Heatmap for feature correlation
- Feature importance bar graph
- Confusion matrices
- ROC curves comparing models
