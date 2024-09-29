
# Credit Risk Modeling Project

This project involves building, monitoring, and calculating the expected loss of a credit risk model. The project is divided into several notebooks that cover different phases of the credit risk modeling process. Below is a brief description of each notebook:

## 1. Data Preparation
The first step in the project is preparing the dataset for modeling. This notebook focuses on:
- Cleaning the data
- Handling missing values
- Feature engineering
- Splitting the data into training and testing sets

## 2. Monitoring
Once the model is deployed, its performance needs to be monitored regularly to ensure it continues to perform accurately. This notebook covers:
- Backtesting the model
- Monitoring its accuracy over time
- Validating the model performance

## 3. Probability of Default (PD) Model
The PD model predicts the likelihood that a borrower will default on a loan. This notebook covers:
- Building the PD model using statistical or machine learning techniques
- Evaluating the model's accuracy
- Fine-tuning hyperparameters to improve performance

## 4. Calculating Expected Loss
Expected loss is a key output of credit risk models, and it combines three components:
- **Probability of Default (PD)**: The likelihood of a borrower defaulting
- **Loss Given Default (LGD)**: The amount of loss if a borrower defaults
- **Exposure at Default (EAD)**: The amount outstanding at the time of default
This notebook calculates the expected loss based on these components.

## How to Use
1. Clone or download the project repository.
2. Install the necessary dependencies using:
    ```
    pip install -r requirements.txt
    ```
3. Run the notebooks in the following order:
    - Credit Risk Modeling - Preparation.ipynb
    - Credit Risk Modeling - PD Model.ipynb
    - Credit Risk Modeling - Monitoring.ipynb
    - Credit Risk Modeling - Calculating Expected Loss Complete.ipynb

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries (install using requirements.txt):
    - pandas
    - numpy
    - sklearn
    - matplotlib
    - seaborn

## License
This project is licensed under the MIT License.
