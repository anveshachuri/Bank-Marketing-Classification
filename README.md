# Bank Marketing Classification

This project aims to build a machine learning model to classify the outcomes of a marketing campaign conducted by a bank. The objective is to predict whether a client will subscribe to a term deposit based on various attributes provided in the dataset.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)

## Introduction

Bank marketing campaigns are essential for financial institutions to promote their products. The goal of this project is to use machine learning techniques to classify whether a client will subscribe to a term deposit based on features such as age, job, marital status, education, and more. This project provides a step-by-step guide from data loading and preprocessing to model training and evaluation.

## Dataset

The dataset used in this project is the "Bank Marketing" dataset from the UCI Machine Learning Repository. It contains various socio-economic attributes and details about previous marketing contacts with the client.

- **Source:** UCI Machine Learning Repository
- **File:** `bank-additional-full.csv`
- **Attributes:**
  - Age
  - Job
  - Marital status
  - Education
  - Default
  - Housing loan
  - Personal loan
  - Contact communication type
  - Last contact month
  - Last contact day of the week
  - Duration of the last contact
  - Campaign: number of contacts performed during this campaign
  - Pdays: number of days that passed by after the client was last contacted from a previous campaign
  - Previous: number of contacts performed before this campaign
  - Poutcome: outcome of the previous marketing campaign
  - Emp.var.rate: employment variation rate
  - Cons.price.idx: consumer price index
  - Cons.conf.idx: consumer confidence index
  - Euribor3m: 3-month EURIBOR rate
  - Nr.employed: number of employees
  - Y: target variable (yes/no)

## Installation

To run this project, you'll need Python and the following libraries:

- pandas
- numpy
- seaborn
- matplotlib

You can install these libraries using pip:

```sh
pip install pandas numpy seaborn matplotlib
```
## Usage

1. Clone the repository

   ```sh
   git clone https://github.com/yourusername/bank-marketing-classification.git
    cd bank-marketing-classification
   ```
   
2. Open the Jupyter notebook

   ```sh
   jupyter notebook bank_marketing.ipynb
    ```

3. Run the cells sequentially to preprocess the data, train the model, and evaluate its performance.

## License

This project is licensed under the MIT License. See the [LICENSE](#LICENSE) file for details.


