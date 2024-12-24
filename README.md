# Lending Club Case Study


## Table of Contents
1. **[Import Libraries](#lib)**
2. **[Set Options](#opt)**
3. **[Read Data](#read)**
4. **[Understand Data](#understand)**
    - 4.1 - [Data Types](#dtype)
    - 4.2 - [Summary Statistics](#desc)
    - 4.3 - [Missing Values](#missing)
5. **[Data Cleaning](#preprocess)**
    - 5.1 - [Missing Values Treatment](#treat)
    - 5.2 - [Outlier Treatment](#outlier)
    - 5.3 - [Encode Categorical Variables](#encode)
6. **[Exploratory Data Analysis](#eda)**
    - 6.1 - [Univariate Categorical Analysis](#uni_cat)
    - 6.2 - [Univariate Continuous Analysis](#uni_cont)
    - 6.3 - [Segmented Univariate Analysis](#seg_uni)
    - 6.4 - [Bivariate Categorical Analysis](#bi_cat)
    - 6.5 - [Bivariate Continuous Analysis](#bi_cont)
    - 6.6 - [Multivariate Analysis](#multi)
7. **[Conclusions](#conclusions)**

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
- This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

- In this case study, develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## Objective
- If one is able to identify these `risky loan applicants`, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

- In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

- To develop understanding of the domain, you are advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. **Loan Status and Interest Rates**:
    - Defaulters tend to have higher interest rates compared to non-defaulters.
    - High interest rates are more likely to result in loan defaults.

2. **Loan Amount and Loan Status**:
    - Higher loan amounts are associated with higher risk of default.
    - Applicants with higher loan amounts should be scrutinized more closely.

3. **Employment Length and Loan Status**:
    - Applicants with unstable employment lengths and low loan amounts are riskier.
    - Despite stable employment lengths, some applicants with high loan amounts still default.

4. **Home Ownership and Loan Status**:
    - Applicants with rented homes have a higher risk of default compared to those with mortgage or owned homes.

5. **Purpose of Loan and Loan Status**:
    - Certain loan purposes, such as debt consolidation, have higher total loan amounts and higher default rates.
    - Applicants applying for loans for high-risk purposes should be evaluated carefully.

6. **Income Class and Loan Status**:
    - Upper-class applicants have the highest average default loan amounts.
    - Lower-class applicants have the lowest average default loan amounts.

7. **Geographical Analysis**:
    - States like California (CA) and New York (NY) have the highest total loan amounts and highest default amounts.
    - Applicants from these states should be assessed with additional caution.

8. **Grade and Loan Status**:
    - Loans graded `F` have the highest interest rates and are more likely to default.
    - Loans graded `A` have the lowest interest rates and are less likely to default.
    - Interest rates gradually increase from `Grade A` to `Grade G`.

9. **Loan Term and Loan Status**:
    - Long-term loans (60 months) have higher default rates due to higher risk.
    - Short-term loans (36 months) have lower default rates due to lower risk.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy      - v2.1.2
- Pandas     - v2.2.3
- Matplotlib - v3.9.2
- Seaborn    - v0.13.2

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- References
  - [Matplotlib](https://matplotlib.org/stable/)
  - [Pandas](https://pandas.pydata.org/)
  - [Seaborn](https://seaborn.pydata.org/)


## Contact
Created by [@kushknows] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->