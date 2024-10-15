# Marketing Campaign Analysis

This project is aimed at analyzing customer behavior from a marketing campaign dataset. The data contains various features such as customer demographics, spending behavior, and responses to promotions, which will be used to generate insights for targeted marketing strategies.

## Features
The dataset contains the following key features:
- **Customer ID**: Unique identifier for each customer.
- **Age**: Customer's age.
- **Income (in $K)**: Customer's annual income in thousands.
- **Spending Score (1-100)**: A score that indicates how much a customer is likely to spend.
- **Gender**: Male or Female.
- **Marital Status**: Whether the customer is married or not.
- **Children**: Number of children the customer has.
- **Promotion Response**: Whether the customer responded to a promotional offer.
- **Buy or Not Buy**: Indicates if the customer bought or did not buy the product.
- **Product Category**: Customer's preferred product category (e.g., Cosmetics, Electronics, Apparel).

## Tools and Libraries
The following Python libraries are used in this project:
- **Pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computations.
- **Plotly**: For creating interactive visualizations.
- **Matplotlib** and **Seaborn**: For static visualizations.
- **Scikit-learn**: For clustering and other machine learning algorithms.

## Data Analysis Steps
1. **Data Loading**: The dataset is read from an Excel file.
2. **Data Cleaning**: Handle missing values and preprocess data.
3. **Exploratory Data Analysis**: Investigate customer attributes, spending patterns, and promotional responses.
4. **Clustering**: Apply KMeans clustering to group customers based on similar behavior.
5. **Classification**:
   - **K-Nearest Neighbors (KNN)**: Applied to predict whether customers Buy or Not Buy.
   - **Naive Bayes**: Applied to predict whether customers Buy or Not Buy.

## How to Run
To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/marketing-campaign-analysis.git
   cd marketing-campaign-analysis
