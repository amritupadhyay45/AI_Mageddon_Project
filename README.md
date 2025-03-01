# Intrusion detection system with AI

## Project overview

The Intrusion Detection System (IDS) with AI is a security solution that leverages artificial intelligence and machine learning techniques.  It detects unauthorized access, malicious activities, and potential cyber threats in a network. 

**Explore the project directly on Google Colab:** [Intrusion_detection_system](https://colab.research.google.com/drive/1D0Q-kTVpjDx9C_3doIqVrV2ptYaF0wFe?usp=sharing)

## Key Features


- **AI-Powered Threat Detection**: Utilizes machine learning models to detect known and unknown threats.
- **NSL-KDD Dataset**: Utilizes the comprehensive NSL-KDD dataset for training and evaluation
- **Multi-Class Classification**: Detects multiple types of network attacks
- **High Performance**: Achieves state-of-the-art detection rates and low false positive rates
- **Scalability**: Can be deployed on small and large networks.

## Dataset Information

The NSL-KDD dataset is a refined version of the KDD'99 dataset, addressing many of the original dataset's limitations:

**Dataset Link:** [NSL-KDD DATASET](https://www.kaggle.com/datasets/hassan06/nslkdd)

## Installation

### Prerequisites

- Python 3.8+
- Scikit-learn
- Numpy
- Pandas

### Setup

```bash
# Clone the repository
git clone 

# Navigate to the project directory
cd intrusion-detection-ai

# Install required dependencies
pip install -r requirements.txt
```

 ## Evaluation Metrics

The performance of the sentiment analysis models was evaluated using the following metrics:

- **Accuracy:** Measures the overall correctness of the classification.
- **F1-Score:** Harmonic mean of precision and recall, useful for imbalanced datasets.
- **ROC-AUC Score:** Area under the Receiver Operating Characteristic (ROC) curve, which measures the model's ability to distinguish between positive and negative classes.
- **Precision**: Indicates how many of the detected threats were actually malicious.
- **Recall**: Represents the system’s ability to detect actual threats.
- **False Positive Rate (FPR)**: The proportion of benign activities incorrectly classified as threats.
- **False Negative Rate (FNR)**: The proportion of actual threats missed by the system.


## Model Architecture

Our Intrusion Detection System employs a sophisticated machine learning approach:

- **Input Processing**: Advanced feature engineering and preprocessing
-** Feature Extraction Layer**: Uses statistical and machine learning techniques to identify important patterns.
- **Model Type**: Deep Neural Network / Ensemble Learning
- **Classification Types**:
  1. Normal Connection
  2. DoS (Denial of Service)
  3. Probe
  4. R2L (Root to Local)
  5. U2R (User to Root)
     

## Performance Metrics

| Metric | Score |
|--------|-------|
| Accuracy | 99.98%|
| Precision | 100% |
| Recall | 99.95% |
| F1 Score | 99.97% |


## Usage





