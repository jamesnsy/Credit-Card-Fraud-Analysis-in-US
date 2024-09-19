# Tackling Credit Card Fraud in US

Analysing credit card fraud patterns in US. Interactive Tableau storyboard can be found [here](https://public.tableau.com/views/CapstoneProject_NeoSiYang881G/TacklingCreditCardFraudinUS?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link).

**Tools:** Excel, Tableau

## Problem Statement:
- A bank manager from Remora, a multinational bank from US, received feedback that there has been a rise of complaints from customers due to unauthorised credit card transactions. The bank manager instructed a data analyst from the fraud department to investigate the underlying patterns behind credit card frauds and what are the possible measures to protect their customers from being a credit card fraud victim.

## Objectives:
- Investigate distribution of fraud cases across gender and age groups.
- Identify regions in the US that are susceptible to credit card fraud.
- Determine the typical times when credit card fraud incidents commonly occur.
- Examine what are the risky merchant categories.
- Propose business recommendations based on previous findings.

## Dataset:
- The chosen dataset is a simulated credit card transaction dataset that contains both legitimate and fraudulent transactions from June to December 2020.
- Only the test dataset (fraudTest.csv) is used for the analysis.
- Contains 555719 rows, 23 fields (columns).
- Kaggle dataset URL: https://www.kaggle.com/datasets/kartik2112/fraud-detection?select=fraudTest.csv
- Acknowledgement goes to Brandon Harris for the creation of dataset.

## Data Cleaning/Preparation using Excel:
- CSV file is converted to Excel file to preserve data format.
- A column name “index” was added, and this represents the unique identifier for each row.
- Null values were checked, no missing data under each field.
- Renaming of column name for better clarity:
1) amt to trans amt (transaction amount)
2) In the “merchant” column, removed the “fraud_” in front of all merchant names.
- Added 3 extra columns:
1) age (age of credit card holders)
2) full name (full name of credit card holders)
3) outcome (label 1 as fraudulent, 0 as not fraudulent)

Processed data can be found [here](https://docs.google.com/spreadsheets/d/1s1KghazIXfj1ZsM40YOrDh02K0Wos-Ws/edit?usp=drive_link&ouid=110997760581773554407&rtpof=true&sd=true). File size is too large to be uploaded to github.

## Summary of Insights:
- Overall, there are **2145** fraudulent transactions and **$1,133,325** losses in total from Jun to Dec 2020.
- Both genders show no significant difference in terms of fraud count and amount, indicating equal vulnerability to credit card fraud. Credit card fraud impacts individuals across all age groups, with a majority falling within the Generation **X**, **Y**, and **Baby Boomer** categories, specifically within the age range of **30 to 59** years old.
- Most fraud incidents occur on the **East Coast (Eg: New York, Pennsylvania)** of the USA, primarily in states characterised by high population density and wealth.
- **Online shopping** recorded the highest fraud count at **506** and the highest average transaction losses at **$994.32**, while **travel** recorded the lowest fraud count at **40** and the lowest average transaction losses at **$8.70**.
- Fraudulent activities are most prevalent on **Sundays, Tuesdays, and Thursdays**. One noticeable trend is the common occurrence of fraudulent activities during **late-night hours**, specifically from **22:00 to 03:00** throughout the week.

## Recommendations:
- Conduct regular **educational programs** for customers from age **30-59** to raise awareness about the types of card fraud, possible causes and preventive measures. Such programs not only reduce card fraud occurrence but also allow bank to demonstrate their commitment to customer’s well being. Informed customers are likely to have greater trust in the bank, leading to **increased loyalty and retention**.
- Bank can encourage shopping merchants, particularly those located in high-fraud regions like the **eastern states** of the USA, to adopt **secure payment methods**. Eg: For online payments, merchants can consider leveraging secure payment gateways, incorporating features such as end-end encryption and tokenization to ensure the secure transfer of online payment data. By doing so, bank indirectly contribute to the reduction of fraudulent transactions. This, consequently, results in **reduced financial losses** pertaining to chargebacks.
- Consider implementing a **fraud detection system** that utilises artificial intelligence to flag potential fraudulent transactions in real time. This system will automatically block suspicious transactions, regardless of their size. Fraud detection systems should be actively operational during late-night hours from **2200 to 0300** daily. Investing in such systems not only protects customers from credit card fraud, but also demonstrates the bank's commitment to safeguarding its customers' financial interests.


















