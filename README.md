# Deep Learning for Healthcare Final Project (Team 16)
**COVID-19 CT Scan Classification with Deep Learning**
- **Paper Name**: Deep learning enables accurate diagnosis of novel coronavirus (COVID-19) with CT images
- **Paper Link**: https://www.medrxiv.org/content/10.1101/2020.02.23.20026930v1
- **GitHub Repo**: https://github.com/biomed-AI/COVID19-CT
  
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

The notebook is structured to provide a streamlined experience with ***a single click "Run All"*** , you will get:

- **Data Loading**: The dataset is automatically loaded and preprocessed.
- **Model Training**: A deep learning model is trained to classify CT scans.
- **Evaluation**: The trained model is evaluated to assess its performance.

## Data Loading & Model Training & Evaluation
As mentioned before, ***when you click "run all," all the steps will be automatically executed without interference***.
<br>
If you want to review the code and check the immediate output for the steps, please do the following:
- For data Loading, please refer to **Methodology**, **III. Data**, **iii. Preprocessing Code & Command and Further Descriptions**.
- For Model Training, please refer to **Methodology**, **V. Training**,  **iv. Training code**.
- For Model Evaluation, please note we use the ***pre-trained*** model. Please refer to **Methodology**, **VI. Evaluations**, **ii. Evaluation Code**.

## Pre-trained Models
- You can download pre-trained models here:
- https://drive.google.com/uc?id=1vGOnn_KPy9InVgGdymivurewcWIK5f0X
  
***Note*** The notebook will automatically download the pre-trained model for testing and evaluation purposes.

## Results
The performance metrics achieved for reproducing the model are as follows:

| Model Description       | AUC  | Accuracy |
|-------------------------|------|----------|
| Our Reproduced Code*    | 0.93 | 0.90     |
| Model from the Paper    | 0.90 | 0.86     |

Note that our reproduced model performs better than the measures in the paper.

**Note:**
* *We use the pre-trained model (see previous section) to accelerate the process.*

## Contributions

Contributions to this project are welcome. Please follow the standard GitHub pull request workflow.

- Fork the repository.
- Make your changes.
- Submit a pull request.

## Acknowledgments

- Original dataset and pre-trained model provided by https://github.com/biomed-AI/COVID19-CT.
- The project is built using PyTorch and supported by Google Colab's computational resources.
