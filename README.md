<div align="center">
  <h1>Customer Shopping Pattern Analysis Dashboard</h1>
</div>

![Power BI](https://img.shields.io/badge/Power%20BI-FFC55C?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAtUlEQVR4nO2ZsQ3CMBBFLTMIlBkOhgizxINA5CI3AhTJAMkEFEdDWtDJjmyF96Tf39c9y5LtHABsztz5uISDWjJ3vne1YB1++cTVAgVKwwZKwwZKwwa2RocmqjRqyet2qucisw6/ZqFAJthA4AykgUIBhXaukI5t1OmqpjzPFRWYjMOvoUAm2IBwBtJAIUGhNFBIUCgNFBIUSgOFBIX+XaGx7c3DPy4/HneP379Zg79nKwCwY94mH/S29nqOhAAAAABJRU5ErkJggg==&logoColor=black)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0000B9.svg?style=for-the-badge&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAADAAAAAwCAYAAABXAvmHAAAACXBIWXMAAAsTAAALEwEAmpwYAAADv0lEQVR4nO2ZvWsUQRjGZ97VJogfaSSFQbC5bWyUYGMRsbWwsBObgIWFMWBmLid4gtGZBNTOzn9ABEHZGMzsLRo/Ck935hRUSBELQQIKIrkLEjMyG8479T5mde8L7oEpd+f57b4z88wMQn311VfH5FBxDKhY2sZfPXMfFA+jXhIQMQbUXwfqayctNty5ona94suUVzyFshpQNwuoGAcqNoz5cosAKu21ATmQ11tRd0ljTMRstXGoDRC11Nzqsuutjh+4pwc67RyhbLAFE3GrlnmoA/CrecWV1NzqBNIad8j8vQFMhFfPPDQDqIBk2m8+vbgLiHjSyDzYA3xsr/nMoyGgvmpmHmwB5oq6febP+/vMHG9jHloCYAYMD0cQC/fGNj8ZHAQiVmzNQ+IA194MYq4C4EoDU+uYyWl0+7Zj86gzKUaB+F/jmIdEAfibYeDybWS+qhkgNJ0famieiuNARCmWeSJKkM6dTgwAuFr803ylyU8Ok0dqPjeZOwPE/xHvy4t36LzYb55PDoDJz/UBNksKmLxYnVcgLWjcksFE3EF0YUf5HYkBYC4vNwQolxSTD9GVwm5MxPWY5tdMFvqzXzexMaA1xkxdsoEAJktwYTFOySwjIkZqdesmPY0Cl2eByx/NIZSG7HMNNNe4ZKh/F40HO+v157ZiIQMWngSmvlv9jct5Demg1lf/bsZIs77cVq3EDiscBS6/WUFcDTVkHlUDfEAkOGTTj9vSKMHDEeDyixWEadnnGhP/PpqYH7Ttwm0pABEjkAm+RF/YEgKz8L5Z0TsO4KQXjgIR36KSyAQarryyhgAuPyCuOldCQMXJaBBWD8opA5G3hzCTACu0fxADyZ2tGw3Suc1Zx/pPRAvfXXQjbMc0qjGm/qXmi5KBeFGKAwFMLUcRvZUAmPrTVlmG+g/RlNiNubweD0KuAVOtixJA/c9NzK8DFRdRNlsJc6xAY0FsxvM7iOeTD3NA/cf1s7v/yaF+7Tg9o85YRY/f/8Y7NFtINk4jujAMRLz9O/76gdmkN3rUYeFx4DLeuOCyBKyQ3IYm0sT8oDFcLhkzLtAJyy3lTDgKXH2NW1Ju8uuAxmZzji7M70FxNVM4CFytdBjgPzX7eh8wudS7AEbT+SFgUvUugBEr7AKuniQC4LX7aLGsbH4Ac+n9L0DKK051BiCCCLZgrm79E4AXHa+f69zxevWBAZeztgCprrrgqJLJQsDkRgOAbr1iqgi4HIsOybjSDpe9dclXlsPkMeDq/fabS0977pq1r75Qd+gnbk39qO0MuGMAAAAASUVORK5CYII=&logoColor=white)
![Python](https://img.shields.io/badge/python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

---

### Table of Contents
- [Background](#background)
- [Business Question](#business-question)
- [Data Overview](#data-overview)
- [Data Preparation](#data-preparation)
- [Analysis](#analysis)
- [Conclusion](#conclusion)
- [Getting Started](#getting-started)
- [License](#license)

---

## Background

Understanding customer shopping patterns is crucial for making informed business and marketing decisions. We are social animals influenced by their surroundings. The shopping pattern of a customer is influenced by various factors such as demographics, preferences, and behavior. Analyzing customer shopping patterns can help businesses identify trends, preferences, and opportunities to improve their marketing strategies and customer service.

---

## Business Question

The business question is to analyze the shopping patterns of customers and identify key trends and insights that can help businesses improve their marketing strategies and customer service.

---

## Data Overview

The dataset contains detailed transactional data across various product categories, customer demographics, and purchase channels. Key features may include:

- Transaction Details: Purchase date, transaction value, product category, and payment method.
- Customer Information: Age group, gender, location, and loyalty status.
- Shopping Behavior: Frequency of purchases, average spend per transaction, and seasonal trends.

---

## Data Preparation

- **Data Loading**: Import the dataset into Power BI using Python script.
- **Data Cleaning**: There is no missing data in the dataset. However, we need to convert the data types of some columns.
- **Data Formatting**: Format the data to ensure consistency and accuracy in the analysis.

---

## Analysis

The visualization is intended to provide an understanding of customer shopping patterns and business performance at two granularities: overviews and regional insights. It is designed to cater to different stakeholders, including business owners, who need a quick grasp of the status quo, marketing teams, and sales teams, who need detailed and actionable insights to make informed decisions.

Overviews provide a high-level summary of key metrics, while regional insights provide a detailed analysis of customer behavior by region. The regional insights enable a localized approach to marketing and sales strategies, taking into account regional preferences and trends based on the demographic.

The dashboard incorporates the temporal aspect of customer shopping patterns, such as seasonal trends and customer behavior over time. This allows businesses to zero in on specific time periods to identify patterns and trends that can help them optimize their marketing strategies and customer service.

| Title                        | Description                                                         |
|-------------------------------|---------------------------------------------------------------------|
| **Overview**        | ![Overview Interaction Animation](assets/animation/overview_interaction.gif)                                             |
| **Detailed State Sales** | ![Drilldown Interaction Animation](assets/animation/drilldown_interaction.gif)                                          |

---

| Metric                        | Description                                                         |
|-------------------------------|---------------------------------------------------------------------|
| **Total Sales Amount**        | Total revenue generated                                             |
| **Average Transaction Value** | Mean spend per transaction                                          |
| **Total Number of Customers** | Total distinct customers                                            |
| **Customer Satisfaction**     | Overall satisfaction score                                          |

---

## Conclusion

Constrained by the scope of the dataset, this visualization attempts to provide a snapshot of customer shopping patterns and business performance. The insights derived from this visualization can serve as a starting point for further analysis and exploration of customer behavior and preferences as below:

| Visualization | Business Questions |
|---------------|----------|
| **Subscription rate of customers** | What customer demographics are most likely to subscribe? <br>What is the average spend of subscribed customers compared to non-subscribed customers? <br>What customer demographics are most likely to subscribe? |
| **Sales by region** | What is the potential revenue increase from increasing the subscription rate? <br>What is the projected revenue based on current sales trends? <br>What is the market share of each region, deriving from the existing customer base? <br>How to position the business in the market to capture the opportunity? |
| **Popular products** | What products are most popular among customers? <br>Are the customer more susceptible to purchasing certain products due to specific marketing strategies, like promotion? If so, on what platform? |
| **Shopping frequency and shipping method** | Is there a relationship between shopping frequency and preferred shipping methods? <br>What are the factors driving the decision of customers to choose a specific shipping method? <br>From the current shipping method selection trend, what is the projected revenue increase from optimizing the shipping method? |

## Getting Started

To work on this project locally, clone the repository by running:

```bash
git clone https://github.com/gary3456/Customer-Shopping-Viz.git
```

Then, navigate to the project folder (it will be created locally with the repository name):

```bash
cd Customer-Shopping-Viz
```

Feel free to submit pull requests with improvements.

## License

This project is licensed under the Batch License.

![Batch](https://img.shields.io/badge/License-MIT-Yellow)
````
