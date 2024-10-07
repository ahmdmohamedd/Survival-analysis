# Customer Retention Survival Analysis

## Overview

This project employs survival analysis techniques to assess customer retention using a dataset containing demographic and usage data. By implementing the Kaplan-Meier estimator, we analyze the likelihood of customer churn over time. The results provide insights into retention patterns, helping businesses improve customer engagement strategies and reduce churn rates.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Results](#results)
- [Contributing](#contributing)

## Installation

To run this project, you need to install the required libraries. You can do this using pip:

```bash
pip install lifelines pandas matplotlib seaborn
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/Survival-analysis.git
   cd Survival-analysis
   ```

2. Open the Jupyter Notebook and run the cells to perform the survival analysis on the customer retention dataset.

3. Modify the dataset or analysis parameters as needed to fit your specific requirements.

## Dataset

The dataset used in this analysis includes the following columns:

- **CustomerID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **Gender**: Gender of the customer.
- **Tenure**: The duration (in months) the customer has been with the service.
- **Usage Frequency**: Frequency of usage of the service.
- **Support Calls**: Number of support calls made by the customer.
- **Payment Delay**: Delay in payment (in days).
- **Subscription Type**: Type of subscription (e.g., Standard, Basic).
- **Contract Length**: Length of the contract (e.g., Annual, Monthly).
- **Total Spend**: Total amount spent by the customer.
- **Last Interaction**: Time since the last interaction (in months).
- **Churn**: Indicates whether the customer has churned (1 if churned, 0 if still active).

## Results

The analysis provides insights into customer retention rates and factors influencing churn. The Kaplan-Meier survival curve illustrates the probability of retention over time.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or raise an issue.
