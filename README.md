# Target Business Case Study: Deep Dive for Strategic Insights

## 📊 Project Overview

This project involves a comprehensive analysis of Target's operations in Brazil, leveraging a real-world e-commerce dataset to uncover strategic insights. The analysis aims to help Target understand customer behavior, operational efficiency, and market dynamics to drive data-driven business decisions.

## 🎯 Problem Statement

Target is a globally renowned brand and one of the leading retailers in the United States. This case study focuses on analyzing Target's operations in Brazil, specifically examining 100,000 orders placed between 2016 and 2018 across multiple marketplaces. The goal is to extract meaningful insights that can help Target optimize its operations, improve customer experience, and enhance business performance.

### Key Objectives

- **Customer Analysis**: Understand customer demographics, behavior patterns, and preferences
- **Operational Insights**: Analyze order fulfillment, delivery performance, and operational efficiency
- **Sales Performance**: Evaluate product categories, pricing strategies, and revenue trends
- **Seller Analytics**: Assess seller performance and geographic distribution
- **Customer Satisfaction**: Analyze review scores and identify factors affecting customer satisfaction
- **Payment Analysis**: Understand payment methods and transaction patterns

## 📁 Dataset Description

The project uses 8 comprehensive datasets containing information about customers, orders, products, sellers, and transactions:

### Available Datasets

| Dataset | Description |
|---------|-------------|
| **customers.csv** | Customer information including unique IDs, location data |
| **geolocation.csv** | Geographic coordinates for Brazilian zip codes |
| **order_items.csv** | Details of items in each order including pricing and seller information |
| **order_reviews.csv** | Customer reviews and ratings for orders |
| **orders.csv** | Order-level information including timestamps and delivery status |
| **payments.csv** | Payment transaction details including methods and values |
| **products.csv** | Product catalog with categories and specifications |
| **sellers.csv** | Seller information and location data |

> **Note**: The datasets folder is excluded from version control due to large file sizes. Please ensure you have the datasets locally in the `datasets/` directory.

## 🛠️ Technologies Used

- **Database**: MySQL
- **Analysis**: SQL queries for data exploration and insights
- **Language**: Python (for data preprocessing if needed)
- **Version Control**: Git & GitHub

## 📂 Project Structure

```
Target/
├── datasets/               # Data files (not tracked in Git)
│   ├── customers.csv
│   ├── geolocation.csv
│   ├── order_items.csv
│   ├── order_reviews.csv
│   ├── orders.csv
│   ├── payments.csv
│   ├── products.csv
│   └── sellers.csv
├── Target_Case_Study.docx  # Detailed case study documentation
├── Target_Case_Study.pdf   # Case study in PDF format
├── target_review.pdf       # Additional review document
├── .gitignore             # Git ignore file
└── README.md              # Project documentation
```

## 🔍 Key Analysis Areas

### 1. **Exploratory Data Analysis (EDA)**
   - Data quality assessment
   - Missing value analysis
   - Data type validation
   - Statistical summaries

### 2. **Customer Analytics**
   - Geographic distribution of customers
   - Customer segmentation
   - Purchase behavior patterns
   - Customer lifetime value

### 3. **Order & Delivery Analysis**
   - Order trends over time
   - Delivery performance metrics
   - Shipping duration analysis
   - Order status distribution

### 4. **Product & Category Analysis**
   - Top-performing product categories
   - Price distribution analysis
   - Product popularity trends
   - Category-wise revenue contribution

### 5. **Seller Performance**
   - Geographic distribution of sellers
   - Seller ratings and performance
   - Top sellers by revenue
   - Seller-customer distance analysis

### 6. **Payment Analysis**
   - Payment method preferences
   - Transaction value distribution
   - Installment pattern analysis
   - Payment trends over time

### 7. **Customer Satisfaction**
   - Review score distribution
   - Factors affecting ratings
   - Correlation between delivery time and ratings
   - Sentiment analysis of reviews

## 🚀 Getting Started

### Prerequisites

- MySQL Server installed and running
- Access to the dataset files
- Basic knowledge of SQL

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Target
   ```

2. **Obtain the datasets**
   - Ensure all CSV files are placed in the `datasets/` folder
   - Verify file integrity and format

3. **Database Setup**
   - Create a new MySQL database
   - Import the CSV files into respective tables
   - Establish necessary relationships and constraints

4. **Run Analysis**
   - Execute SQL queries to derive insights
   - Document findings and observations

## 📈 Expected Deliverables

- Comprehensive SQL queries for data analysis
- Business insights and recommendations
- Data-driven strategic suggestions for Target
- Visualization of key metrics and trends
- Documentation of findings

## 💡 Business Impact

The insights derived from this analysis can help Target:

- **Optimize Operations**: Improve delivery times and reduce logistics costs
- **Enhance Customer Experience**: Understand pain points and improve satisfaction
- **Strategic Planning**: Make informed decisions about inventory, pricing, and market expansion
- **Seller Management**: Identify and support high-performing sellers
- **Revenue Growth**: Focus on high-value categories and customer segments

## 📝 Case Study Documentation

For detailed problem statements, requirements, and specific analysis tasks, please refer to:
- [Target_Case_Study.pdf](Target_Case_Study.pdf)
- [Target_Case_Study.docx](Target_Case_Study.docx)
- [target_review.pdf](target_review.pdf)

## 👥 Author

**Scaler DSML Business Case Study**

## 📄 License

This project is for educational purposes as part of the Scaler Data Science & Machine Learning program.

---

**Note**: This analysis uses anonymized and publicly available e-commerce data for educational purposes.
