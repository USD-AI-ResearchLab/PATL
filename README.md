# PATL: Pool-based Active Twin Learner from Oracle with Imitation Learning for Early Epidemic Detection

This project leverages imitation learning, specifically the DAgger algorithm, to detect different epidemic diseases like COVID-19, pneumonia and tuberculosis from various data sources. The goal is to improve the accuracy and robustness of epidemic disease detection models using advanced machine learning techniques.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)

## Introduction
This project explores the use of imitation learning, specifically the DAgger algorithm, to enhance the detection of epidemic diseases through multi-modal medical imaging, including CT scans and X-rays. The urgent demand for accurate and efficient diagnostic tools during outbreaks has accelerated advancements in this area.

## Dataset
The datasets used in this project include:
1. **Chest X-ray images** from the [COVID-19 Radiography Database](https://www.kaggle.com/tawsifurrahman/covid19-radiography-database).
2. **CT Scan images** from the [UCSD-AI4H COVID-CT Dataset](https://www.kaggle.com/datasets/hgunraj/covidxct).

## Installation
To get started, clone the repository:

```bash
git clone https://github.com/2ai-lab/PATL.git
```

## Usage
After installation, you can use the notebook file to preprocess data, train models, and evaluate performance:

## Model Training
The training process involves using the DAgger algorithm to iteratively refine the model.

## Evaluation
Model evaluation is performed on a separate test set. Metrics such as accuracy, precision, recall, and F1-score are computed to assess performance.

## Results
The results of the model training and evaluation are stored in the specified directory. Detailed performance metrics and visualizations can be found in the evaluation report.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes. Ensure that your code adheres to the project's coding standards and includes appropriate tests.


