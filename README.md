# Network Intrusion Detection System (NIDS)

This project is a Machine Learning-based Network Intrusion Detection System (NIDS) that detects and classifies different types of network attacks using the KDD Cup dataset.

## Project Overview
The main goal of this project is to identify malicious network activities and classify them into different attack categories such as:
- DoS (Denial of Service)
- Probe
- R2L (Remote to Local)
- U2R (User to Root)
- Normal traffic

## 📊 Dataset
- Dataset used: KDD Cup 99 Dataset
- The dataset contains multiple network traffic features such as:
  - Protocol type
  - Service
  - Flag
  - Source & destination bytes
  - Error rates and many more

## Data Preprocessing
- Removed null values
- Dropped highly correlated features
- Converted categorical data into numeric format
- Normalized data using MinMaxScaler

## Machine Learning Models Used
The following models were implemented and compared:

- Gaussian Naive Bayes
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- Logistic Regression

## Model Performance

### Training Accuracy:
- NB: 87.95%
- DT: 99.05%
- RF: 99.99%
- SVM: 99.87%
- LR: 99.35%

### Testing Accuracy:
- NB: 87.90%
- DT: 99.05%
- RF: 99.96%
- SVM: 99.87%
- LR: 99.35%

## Performance Comparison
The project also compares:
- Training Time
- Testing Time
- Accuracy of models

## Visualizations
- Feature distribution graphs
- Correlation heatmap
- Accuracy comparison charts

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
  
## Future Improvements
- Use Deep Learning models
- Real-time intrusion detection
- Deploy as a web application
- Improve dataset quality


