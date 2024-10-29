# Customer Retention Classification

## About the Dataset

### Context
The goal of this project is to predict customer behavior to enhance retention strategies. By analyzing relevant customer data, organizations can develop targeted customer retention programs. The dataset used in this analysis is derived from [IBM Sample Data Sets].

### Content
Each row in the dataset represents a customer, while each column contains attributes describing that customer. The dataset includes the following information:

- **Churn**: Indicates whether the customer left within the last month (1 = Yes, 0 = No).
- **Services**: The services each customer has signed up for, including:
  - Phone
  - Multiple Lines
  - Internet
  - Online Security
  - Online Backup
  - Device Protection
  - Tech Support
  - Streaming TV and Movies
- **Customer Account Information**:
  - Tenure: How long the customer has been with the company
  - Contract Type: The type of contract (e.g., month-to-month, one year, two years)
  - Payment Method: How the customer pays their bill
  - Paperless Billing: Whether the customer opted for paperless billing
  - Monthly Charges: Monthly charges incurred by the customer
  - Total Charges: Total charges over the customer's tenure
- **Demographic Information**:
  - Gender
  - Age Range
  - Presence of Partners
  - Presence of Dependents

## Project Structure
- `customer_churn.csv`: The dataset used for analysis.
- `notebooks/`: Contains Jupyter Notebooks with data exploration and model implementation.
- `README.md`: Project documentation.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Run
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook in the `notebooks/` directory to explore the data and build the classification model.

## Conclusion
By analyzing the customer attributes and employing machine learning techniques, we aim to identify the factors contributing to customer churn and devise strategies to improve retention.
