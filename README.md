# Bank Customer Data Analysis

## Project Overview

This repository contains an exploratory data analysis (EDA) of bank customers, focusing on variables such as balance, deposit, age, loans, and returns. The aim of the analysis is to uncover the significance of the relationships between these important variables.

## Table of Contents
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Data Description](#data-description)
- [Methodology](#methodology)
  - [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Results](#results)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Project Structure

```
bank-customer-data-analysis/
│
├── data/
│   └── bank_customer_data.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── src/
│   └── data_preprocessing.py
│
├── results/
│   └── eda_visualizations.png
│
├── README.md
└── requirements.txt
```

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/bank-customer-data-analysis.git
    cd bank-customer-data-analysis
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Data Description

The dataset used in this analysis contains information about bank customers, including variables such as balance, deposit, age, loans, and returns. The data file is located in the `data/` directory.

## Methodology

### Exploratory Data Analysis (EDA)

- **Objective:** Understand the structure and key characteristics of the dataset.
- **Tasks:** Data cleaning, handling missing values, visualizing data distributions, and exploring relationships between variables.
- **Output:** Initial insights and identification of significant relationships between key variables.

## Results

The analysis provided insights into the relationships between various customer attributes. Visualizations of the results are saved in the `results/` directory. Key findings include:

- Distribution of customer balances, deposits, and loans.
- Correlations between age, balance, and loan status.
- Insights into customer segmentation based on financial behavior.

## Usage

1. Run the EDA notebook:
    ```bash
    jupyter notebook notebooks/EDA.ipynb
    ```

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
