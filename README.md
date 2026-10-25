# Computational Linguistics & NLP Assignment

## 📌 Overview

This repository contains the Computational Linguistics and Natural Language Processing (CL & NLP) assignment, covering theoretical concepts and numerical problems related to Long Short-Term Memory (LSTM) networks, sequential data processing, time-series forecasting, and classification evaluation.

The assignment focuses on understanding LSTM architecture, performing forward-pass calculations, analyzing trainable parameters, studying gradient behavior, and exploring how sequential models can be applied to prediction and failure detection tasks.

## 📚 Topics Covered

The assignment includes the following major concepts:

### 1. Long Short-Term Memory (LSTM)

LSTM is a type of Recurrent Neural Network (RNN) that uses a memory mechanism to learn dependencies in sequential data.

The assignment covers the primary components of an LSTM cell:

- Forget Gate
- Input Gate
- Candidate Cell State
- Cell State
- Output Gate
- Hidden State

### 2. LSTM Forward Pass

This section involves numerical calculations to understand how an LSTM cell processes an input and updates its internal states.

The calculations include:

- Forget gate activation
- Input gate activation
- Candidate cell state computation
- Cell state update
- Output gate activation
- Hidden state calculation

These operations demonstrate how an LSTM controls the retention and introduction of information at each time step.

### 3. LSTM Parameter Count

The assignment examines how to calculate the total number of trainable parameters in an LSTM layer.

The calculation considers:

- Input feature dimension
- Hidden units
- Input weight matrices
- Recurrent weight matrices
- Bias parameters
- Parameters associated with the four LSTM gates
- Differences between bias configurations

This analysis helps explain the relationship between network architecture and model complexity.

### 4. Vanishing Gradient Problem

The vanishing gradient problem occurs when gradients become progressively smaller during backpropagation through long sequences.

The assignment investigates how forget-gate values affect information retention across multiple time steps and explains how LSTM architecture helps address the limitations of traditional RNNs when learning long-term dependencies.

### 5. Time-Series Prediction Using LSTM

This section explores the preparation of sequential hourly data for an LSTM-based forecasting task.

The concepts covered include:

- Input sequence length
- Forecasting horizon
- Number of input features
- Batch size
- Available training records
- Sliding-window generation
- Mini-batch construction
- Input and output tensor dimensions

These concepts help establish how time-series observations are converted into suitable inputs for sequence-learning models.

### 6. Min-Max Normalization

Min-Max normalization rescales numerical data into a defined range, commonly between 0 and 1.

**Formula:**

\[
X'=\frac{X-X_{\min}}{X_{\max}-X_{\min}}
\]

The assignment examines the application of this transformation and its importance in preparing numerical features for machine learning models.

### 7. Failure Prediction

This section explores the use of an LSTM model's predicted probability to determine whether a failure is expected in the next cycle.

A predefined decision threshold is applied to convert the probability into a binary prediction. This approach illustrates the use of sequence-learning models in predictive maintenance and failure detection.

## 📊 Model Evaluation

The assignment covers the confusion matrix and the calculation of classification metrics used to assess model performance.

The four components of a confusion matrix are:

- **TP – True Positive:** A failure correctly identified as a failure.
- **TN – True Negative:** A normal case correctly identified as normal.
- **FP – False Positive:** A normal case incorrectly classified as a failure.
- **FN – False Negative:** A failure incorrectly classified as normal.

The following evaluation metrics are considered:

### Precision

\[
\text{Precision}=\frac{TP}{TP+FP}
\]

Measures how many predicted positive cases are actually positive.

### Recall

\[
\text{Recall}=\frac{TP}{TP+FN}
\]

Measures how many actual positive cases are correctly detected.

### F1-Score

\[
F1=2\times\frac{\text{Precision}\times\text{Recall}}{\text{Precision}+\text{Recall}}
\]

Provides a combined measure of precision and recall.

### Accuracy

\[
\text{Accuracy}=\frac{TP+TN}{TP+TN+FP+FN}
\]

Represents the proportion of total predictions that are correct.

The assignment also explains why accuracy may be misleading for imbalanced datasets. In failure prediction, a model may correctly classify most normal cases while missing many actual failures, making recall and F1-score especially important.

## 🧠 Key Learning Outcomes

After completing this assignment, the following concepts can be understood:

- Fundamentals and architecture of LSTM networks
- Functionality of LSTM gates and memory states
- Numerical computation of an LSTM forward pass
- Calculation of trainable parameters
- Gradient propagation and the vanishing gradient problem
- Sequential data preparation for time-series prediction
- Training windows, mini-batches, and tensor dimensions
- Min-Max normalization of numerical features
- Probability thresholds for binary classification
- Confusion matrix interpretation
- Precision, recall, F1-score, and accuracy
- Evaluation of classification models on imbalanced datasets

## 📂 Repository Contents

```text
CL-NLP-Assignment/
│
├── README.md
├── CL & NLP Assignment
│    
│
└── Supporting Files/
```

The repository contains the assignment document and any supporting materials related to the Computational Linguistics and Natural Language Processing coursework.

## 🔍 Applications of LSTM

LSTM networks are widely applicable to sequential learning tasks, including:

- Natural Language Processing
- Text Generation and Prediction
- Sentiment Analysis
- Machine Translation
- Speech Recognition
- Time-Series Forecasting
- Predictive Maintenance
- Equipment Failure Detection

## 🛠 Concepts & Techniques

- Computational Linguistics
- Natural Language Processing (NLP)
- Recurrent Neural Networks (RNN)
- Long Short-Term Memory (LSTM)
- Deep Learning
- Sequential Data Processing
- Time-Series Analysis
- Min-Max Normalization
- Confusion Matrix
- Classification Evaluation Metrics

## 🎯 Purpose of the Assignment

The objective of this assignment is to develop a strong theoretical and mathematical understanding of LSTM networks and their role in sequential data modelling.

It connects the internal functioning of LSTM cells with practical prediction scenarios and demonstrates how suitable evaluation metrics can be used to assess classification performance, particularly in failure detection problems.

## 👩‍💻 Author

**Pihu Gupta**

Computational Linguistics & Natural Language Processing Assignment

## 📄 Disclaimer

This repository is intended for academic and educational purposes as part of coursework in Computational Linguistics and Natural Language Processing. The content is designed to demonstrate an understanding of LSTM networks, sequential data modeling, numerical computation, and model evaluation.
