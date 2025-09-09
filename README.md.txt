# Credit Card Customer Segmentation

## Project Overview
This project analyses credit card customer data from AllLife Bank to identify distinct customer segments based on spending patterns and interactions with the bank. The goal is to help the marketing and operations teams improve market penetration, personalise campaigns, and enhance service delivery.

The analysis uses unsupervised machine learning techniques (K-Means and Hierarchical Clustering) to segment customers. Key insights include differences in customer behaviour (e.g., online vs. offline interactions) and recommendations for targeted marketing and servicing.

## Objective
- Identify the number of customer segments.
- Analyse differences between segments.
- Provide recommendations to the bank for better marketing and customer service.

Key Questions Addressed:
- How many different segments of customers are there?
- How are these segments different from each other?
- What are the recommendations for marketing and servicing these customers?

## Data Description
The dataset (`credit_card_customers.csv`) contains information on 1000 customers with the following columns:
- **Serial_No**: Unique identifier.
- **Customer_Key**: Customer identifier (note: contains some duplicates).
- **Average_Credit_Limit**: Average credit limit across all cards.
- **Total_Credit_Cards**: Total number of credit cards held.
- **Total_Visits_Bank**: Number of in-person bank visits.
- **Total_Visits_Online**: Number of online visits.
- **Total_Calls_Made**: Number of calls made to the bank.

Data issues noted: 15 duplicate Customer_Key entries (handled in the notebook via grouping and analysis).

## Technologies Used
- Python 3.x
- Libraries: NumPy, Pandas, Matplotlib/Seaborn (for visualization), Scikit-learn (for clustering), SciPy (for hierarchical clustering).
- Jupyter Notebook for analysis.

## Project Structure
- `credit_card_customers.csv`: Raw dataset.
- `credit_card_segmentation.ipynb`: Jupyter notebook with the full analysis, including:
- Part 1: Exploratory Data Analysis (EDA) with univariate analysis, visualisations (histograms, boxplots, pairplots), and insights.
- Part 2: K-Means Clustering (Elbow plot for optimal K, cluster analysis with boxplots).
- Part 3: Hierarchical Clustering (Dendrograms with different linkages, cophenetic coefficient, cluster analysis).
- Part 4: Comparison of clustering methods (silhouette scores), key findings, and answers to project questions.
- `README.md`: This file.

## How to Run the Project
1. Clone the repository:
