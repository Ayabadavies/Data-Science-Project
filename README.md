# Loan Default Risk Prediction

### 📋 Project Overview
This project develops a machine learning pipeline to predict loan default risk using customer behavioral, demographic, and financial data. The solution enables financial institutions to make better credit decisions and minimize financial losses through data-driven risk assessment.

###🎯 Business Problem
Financial institutions face significant challenges in accurately assessing loan default risk. Traditional methods often fall short in today's complex financial landscape, leading to increased financial losses and inefficient credit allocation.

### 📊 Dataset Description
The analysis utilizes three comprehensive datasets:

Performance Data (trainperf.csv): Current loan performance metrics

Demographics Data (traindemographics.csv): Customer demographic information

Previous Loans Data (trainprevloans.csv): Historical loan data for customers

### Key Features:

**1. Demographics:** Age, employment status, education level, geographic location

**2. Financial:** Loan amount, total due, term days, interest calculations

**3. Behavioral:** Approval time, repayment patterns, previous loan history

**4. Target:** Loan default indicator (good_bad_flag)

### 🛠️ Technical Approach

**1. Data Preparation & Cleaning**

Handled missing values and data anomalies

Validated data ranges and business rules

Removed duplicates and irrelevant columns

Engineered new features (interest rates, approval times, repayment metrics)

**2. Exploratory Data Analysis**

Assessed class imbalance in target variable

Analyzed correlation between features

Visualized distributions and relationships

Identified key patterns and risk factors

**3. Feature Engineering**

Created financial ratios and risk indicators

Developed time-based features

Encoded categorical variables

Selected optimal features using various techniques


**📈 Key Insights**

Credit Score Impact: Customers with credit scores below 600 are 4x more likely to default

Employment Risk: Self-employed individuals show 20% higher default rates

Loan Purpose: "Small business" loans demonstrate the highest default rates

Debt Ratios: Loan-to-income ratio > 0.4 and debt-to-income ratio > 0.5 indicate high risk

Demographic Factors: Young borrowers (age < 25) show higher default rates on high-value loans
