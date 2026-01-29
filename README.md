# FinCorp Loan Portfolio Analysis

## 📊 Project Overview

A comprehensive data analysis project focused on FinCorp's loan portfolio and customer behavior to optimize lending operations, minimize defaults, and enhance profitability through data-driven insights.

## 🎯 Objectives

This analysis aims to understand and optimize:

1. **Default Risks and Factors**
   - Identifying customer and loan attributes contributing to defaults
   - Trends in defaults across branches, regions, and loan types

2. **Branch and Regional Efficiency**
   - Evaluating branch performance in loan disbursement, processing time, and recovery rates

3. **Customer Insights**
   - Analyzing demographics, credit scores, and repayment patterns
   - Segmenting customers to identify high-value and high-risk groups

4. **Profitability**
   - Understanding key drivers of profitability through loan disbursement trends, interest income, and recovery efficiency

All tasks and analyses will collectively help Hero FinCorp optimize its loan approval process, reduce defaults, and improve branch efficiency, enabling data-driven decision-making.

## 📁 Project Structure

```
├── CaseStudyAssessment.ipynb             # Case study analysis
├── Hero_FinCorp_Case_Study.docx.pdf      # Detailed case assessment
├── README.md                             # Project documentation
└── Datasets/
    ├── applications.csv                  # Loan applications data
    ├── branches.csv                      # Branch information
    ├── customers.csv                     # Customer demographics
    ├── defaults.csv                      # Default records
    ├── loans.csv                         # Loan details
    └── transactions.csv                  # Transaction records
```

## 📋 Dataset Descriptions

### Customer Demographics
Contains details about FinCorp's customers.

**Key Columns:**
- `Customer_ID`: Unique identifier for each customer
- `Full_Name`: Name of the customer
- `Credit_Score`: Numerical credit rating of the customer
- `Annual_Income`: Yearly income of the customer
- `Employment_Status`: Employment type (e.g., Salaried, Self-Employed)

### Loan Data
Details of all active and closed loans.

**Key Columns:**
- `Loan_ID`: Unique identifier for each loan
- `Customer_ID`: Customer associated with the loan
- `Loan_Amount`: Principal loan amount
- `Interest_Rate`: Annual interest rate on the loan
- `Loan_Term`: Loan repayment duration in months

### Loan Applications
Tracks the loan application process.

**Key Columns:**
- `Application_ID`: Unique identifier for each loan application
- `Approval_Status`: Whether the application was approved or rejected
- `Rejection_Reason`: Reason for rejection (if applicable)
- `Processing_Fee`: Fee charged during the application process
- `Application_Date`: Date of application submission

### Transactions
Record all financial transactions related to loans.

**Key Columns:**
- `Transaction_ID`: Unique identifier for each transaction
- `Loan_ID`: Associated loan for the transaction
- `Transaction_Type`: Type of transaction (e.g., EMI Payment, Penalty)
- `Transaction_Amount`: Monetary amount of the transaction
- `Transaction_Date`: Date of the transaction

### Default Records
Details of customers who defaulted on their loans.

**Key Columns:**
- `Default_ID`: Unique identifier for each default case
- `Loan_ID`: Associated loan for the default
- `Default_Amount`: Amount remaining unpaid
- `Recovery_Amount`: Amount recovered post-default
- `Default_Date`: Date when the default occurred

### Branch Information
Contains information about FinCorp branches.

**Key Columns:**
- `Branch_ID`: Unique identifier for each branch
- `Region`: Geographic location of the branch
- `Total_Active_Loans`: Number of loans currently active in the branch
- `Delinquent_Loans`: Number of overdue loans in the branch
- `Loan_Disbursement_Amount`: Total loan disbursement volume

## 🔍 Analysis Tasks

### 1. Data Quality and Preparation
- Validate and clean the datasets
- Check for missing values, duplicate entries, and inconsistent data
- Standardize date formats and remove irrelevant columns
- Handle outliers in numeric columns like Loan_Amount, Interest_Rate, and Default_Amount

### 2. Descriptive Analysis
Summarize and visualize key metrics:
- Distribution of Loan_Amount, EMI_Amount, and Credit_Score
- Regional trends in loan disbursement and defaults
- Monthly trends in loan approvals and disbursements

### 3. Default Risk Analysis
- **Correlation Between Loan Attributes and Defaults**: Calculate correlations between Loan_Amount, Interest_Rate, Credit_Score, and Default_Flag
- **Pairwise Correlation Analysis**: Create a heatmap to visualize correlations between key variables
- **Correlation Between Branch Metrics and Defaults**: Analyze relationship between branch performance metrics and default rates

### 4. Branch and Regional Performance
Rank branches by:
- Loan disbursement volume
- Processing time efficiency
- Default rates and recovery rates
- Compare branch performance across regions

### 5. Customer Segmentation
- Segment customers by income, credit score, and loan status
- Identify high-risk and high-value customer groups
- Analyze repayment behavior across segments

### 6. Advanced Statistical Analysis
- Correlation Analysis for Default Risks
- Pairwise Correlation Heatmap
- Branch-Level Correlation analysis

### 7. Transaction and Recovery Analysis
- Analyze penalty payments and overdue trends
- Evaluate recovery rates by Default_Reason and Legal_Action
- Compare recovery rates across regions and branches

### 8. EMI Analysis
- Analyze relationship between EMI amounts and default probabilities
- Identify thresholds for EMI amounts where defaults are most likely
- Compare EMI trends across loan types

### 9. Loan Application Insights
- Calculate approval and rejection rates
- Identify most common reasons for loan rejection
- Compare application processing fees between approved and rejected applications

### 10. Recovery Effectiveness
- Determine effectiveness of recovery efforts
- Compare recovery rates for defaults with and without legal actions
- Analyze branch-wise recovery performance

### 11. Loan Disbursement Efficiency
- Analyze time from application to loan disbursement
- Compare average processing times across branches
- Evaluate disbursement trends by loan purpose and region

### 12. Profitability Analysis
- Calculate total interest income generated
- Identify most profitable loan purposes
- Compare profitability metrics for branches across regions

### 13. Geospatial Analysis
- Map distribution of active loans across regions
- Compare default rates across different geographic regions
- Visualize loan disbursement trends for rural vs. urban areas

### 14. Default Trends
- Analyze number of defaults over time
- Calculate average default amount for different loan purposes
- Compare default rates across customer income categories

### 15. Branch Efficiency
- Calculate average loan disbursement time for each branch
- Identify branches with highest number of rejected applications
- Compare branch efficiency based on customer satisfaction metrics

### 16. Time-Series Analysis
- Analyze monthly loan disbursement trends over the last 5 years
- Identify seasonal patterns in loan applications and disbursements
- Compare monthly default rates across regions

### 17. Customer Behavior Analysis
- Categorize customers based on repayment behavior
- Analyze patterns in loan approval and rejection reasons
- Identify high-value customers with consistent repayment histories

### 18. Risk Assessment
- Develop risk matrix for loan products
- Rank loan types by risk level
- Analyze high-risk customer segments by credit score and income

### 19. Time to Default Analysis
- Calculate average time from loan disbursement to default
- Identify loan purposes with shortest time to default
- Compare time to default across customer demographics

### 20. Transaction Pattern Analysis
- Identify customers with irregular repayment patterns
- Analyze penalty payments as proportion of total transactions
- Compare transaction amounts for overdue vs. non-overdue loans

## 🎯 Collective Agenda

The collective agenda is to provide Hero FinCorp with actionable recommendations to:

1. **Minimize loan defaults** by identifying high-risk customers and regions
2. **Optimize branch operations** by improving processing time and recovery rates
3. **Enhance profitability** through better customer segmentation and interest income strategies

## 📦 Deliverables

### 1. Key Insights Report
Summarize findings for each task, including key metrics and insights

### 2. Visualizations
Provide plots, charts, and heatmaps to support findings

### 3. Recommendations
Strategies for reducing defaults, optimizing branch performance, and improving profitability

## 🛠️ Technologies Used

- **Python**: Primary programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development environment

## 👤 Author

**Arnab Bera**

## 📄 License

This project is for educational and analytical purposes.
