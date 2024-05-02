# Deep Learning for Healthcare Final Project (Team 16)
**COVID-19 CT Scan Classification with Deep Learning**

## Introduction
This repository contains a Jupyter Notebook that demonstrates the classification of COVID-19 cases from CT scans using deep learning techniques. The provided notebook can be executed in a Google Colab environment without requiring additional setup.

## Quickstart

1. Open the `DL4H_Team_16.ipynb` notebook in **Google Colab**.
2. To execute all cells, Click "Run All" in the Runtime menu.
3. The entire process should be completed in approximately 8 minutes.

## Features
- Provide `demo_mode` to run a subset in a shorter time (Within 8 minutes in Google Colab).
- Preprocessed datasets for COVID/non-COVID cases.
- Pretrained model checkpoint for quick validation.
- The entire workflow is contained within a single notebook for ease of use.

## Requirements

- A Google Colab account.
- No external packages are required as all dependencies are handled by the notebook.
- Here's the common hardware specifications in Google Colab:
### 1. CPU Specifications:
- 2 x Intel(R) Xeon(R) CPU @ 2.30GHz
- Single core with 2 threads per CPU

### 2. GPU Specifications:
- NVIDIA Tesla T4
- 15 GB memory available

## Overall Workflow

The notebook is structured to provide a streamlined experience with*** a single click "Run All"***, you will get:

- **Data Loading**: The dataset is automatically loaded and preprocessed.
- **Model Training**: A deep learning model is trained to classify CT scans.
- **Evaluation**: The trained model is evaluated to assess its performance.

## Data Loading & Model Training & Evaluation
As mentioned before, when you click "run all," all the steps will be automatically executed without interference.
<be>
If you want to review the code and check the immediate output for the steps, please do the following:
- For data Loading, please refer to **Methodology**, **III. Data**, **iii. Preprocessing Code & Command and Further Descriptions**.
- For Model Training, please refer to **Methodology**, **V. Training**,  **iv. Training code**.
- For Model Evaluation, please note we use the ***pre-trained*** model. Please refer to **Methodology**, **VI. Evaluations**, **ii. Evaluation Code**.



## Contributions

Contributions to this project are welcome. Please follow the standard GitHub pull request workflow.

- Fork the repository.
- Make your changes.
- Submit a pull request.

## License

This project is licensed under the terms of the MIT license.

## Acknowledgments

- Original dataset and pre-trained model provided by https://github.com/biomed-AI/COVID19-CT.
- The project is built using PyTorch and supported by Google Colab's computational resources.
