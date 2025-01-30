---

# Food Delivery Cost and Profitability Analysis

This repository contains a comprehensive analysis of the cost structure and profitability of a food delivery service using a dataset of food orders in New Delhi. The analysis aims to examine key metrics like delivery times, commission fees, order values, and customer payment preferences to assess the financial health and performance of the service.

## Project Overview

The project focuses on analyzing the food delivery process and its profitability, considering several factors such as:

- Delivery fees
- Commission fees
- Order values
- Customer payment methods
- Refunds/Chargebacks

The goal is to derive insights that can inform business decisions and improve operational efficiency. Key objectives include understanding the cost components of the food delivery service, evaluating the most common payment methods, and calculating the impact of discounts and promotions.

## Key Analysis Tasks

1. **Data Cleaning:** The dataset was cleaned to remove inconsistencies, handle missing values, and convert data types for proper analysis.
2. **Proportion Analysis:** The most common payment methods were analyzed, and their proportions calculated.
3. **Confidence Interval Calculation:** The 95% confidence interval for the most common payment method was determined.
4. **Commission Fee Analysis:** The average and median commission fees were computed to understand the cost structure.
5. **Order Value Analysis:** The average order value for customers was calculated.
6. **Probability Calculations:** Various probabilities related to commission fees were determined.
7. **Delivery Time Analysis:** Delivery times for credit card orders were examined, along with a hypothesis test on delivery times.
8. **Refund and Chargeback Distribution:** The distribution of payment methods associated with refunds and chargebacks was analyzed.

## Dataset Description

The dataset, `food_orders_new_delhi.csv`, contains the following columns:

- **Order ID**: Unique identifier for each order.
- **Customer ID**: Unique identifier for each customer.
- **Restaurant ID**: Unique identifier for each restaurant.
- **Order Date and Time**: Date and time when the order was placed.
- **Delivery Date and Time**: Date and time when the order was delivered.
- **Order Value**: Total value of the order.
- **Delivery Fee**: Fee charged for delivering the order.
- **Payment Method**: Method used for payment (e.g., Credit Card, Digital Wallet, Cash on Delivery).
- **Discounts and Offers**: Any discounts or promotional offers applied to the order.
- **Commission Fee**: Fee charged by the platform for processing the order.
- **Payment Processing Fee**: Fee for processing the payment.
- **Refunds/Chargebacks**: Amount refunded or charged back for the order.

## Requirements

- Python 3.x
- Pandas
- NumPy
- Matplotlib (for visualization)
- SciPy (for statistical analysis)

## Setup

Clone this repository and install the required dependencies:

```bash
git clone https://github.com/MadScie254/food_delivery_cost_and_profitability_1.git
cd food_delivery_cost_and_profitability_1
pip install -r requirements.txt
```

## How to Run

1. Download the `food_orders_new_delhi.csv` file.
2. Load the dataset and perform data cleaning and preprocessing.
3. Execute the analysis functions to calculate averages, medians, probabilities, and perform hypothesis testing.

## Results

The analysis produces various insights including:

- Proportions of payment methods
- Confidence intervals for payment method proportions
- Averages and medians of commission fees
- Probability distributions for commission fees
- Delivery time and order value analyses
- Distribution of refunds/chargebacks across payment methods

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
