# ML-Threat-Detection
Machine learning project for threat detection using network datasets. Implements feature selection and classification in Python (Jupyter) to reduce false positives and improve SOC detection accuracy.

<p align="center">
  <a href="./SmartFeatureSelection-Discussion.pdf">
    <span style="font-size:200%; color:Green; font-weight:bold;">
    >> Click Here to View My Report Paper <<
    </span>
  </a>
</p>

## 1. Project Overview

This project applies machine learning techniques to detect network-based threats using the CICIDS2017 dataset from the Canadian Institute for Cybersecurity. The focus is on improving SOC detection accuracy through feature selection and classification while reducing false positives.

## 2. Key Features

1. Implemented in Python using Jupyter Notebooks  
2. Applied filter and embedded feature selection methods  
3. Trained and tested classification models for threat detection  
4. Optimized features to improve accuracy and reduce false positives  
5. Practical use case for SOC analysts applying ML in real-world detection 

## 3. Technology Stack

- Python 3.13.1
- Jupyter Notebook (Anaconda)
- scikit-learn (models, feature selection)  
- pandas, numpy (data handling)  
- matplotlib, seaborn (visualization)
- Kaggle Dataset

## 4. Usage  
### a. Clone this repository  
```
git clone https://github.com/nguye340/ML-Threat-Detection.git

cd ML-Threat-Detection
```

### b. Install dependencies
```
pip install -r requirements.txt
```

### c. Run the Jupyter notebooks

## 5. Results

Improved detection accuracy using optimized feature selection

Reduced false positives for more reliable SOC support

Identified challenges related to imbalanced datasets and unstructured logs

## 6. Repository Structure
```
ML-Threat-Detection/
│── notebooks/
│   │── AnomalyDetectionML_HanThaoNguyen.ipynb
│   │── SmartFeatureSelection_HanNguyen.ipynb
│── AI Models Training in Cybersec Discussion - Han Thao Nguyen.pdf
│── SmartFeatureSelection-Discussion.pdf
│── requirements.txt
│── README.md
```
## 7. Dataset

This project uses the CICIDS2017 dataset, available on Kaggle:
https://www.kaggle.com/datasets/asthana12/cicids2017

Due to file size limits, the dataset is not included in this repository.
The following subsets were used in experiments:

- Monday-WorkingHours.pcap_ISCX.csv
- Tuesday-WorkingHours.pcap_ISCX.csv
- Thursday-WorkingHours-Morning-WebAttacks.pcap_ISCX.csv
- Friday-WorkingHours-Morning.pcap_ISCX.csv
- Friday-WorkingHours-Afternoon-PortScan.pcap_ISCX.csv
- Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv

## 8. Lessons Learned

- Feature selection is critical for effective ML-driven threat detection
- Imbalanced data impacts classifier performance significantly
- Balancing accuracy with minimizing false positives is an ongoing challenge
