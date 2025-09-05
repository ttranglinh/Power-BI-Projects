# Banking Dashboard: Customers & Transaction Analysis
## 1. Business context
- Taking on a role as a Bank Data Analyst, I analyse 20k+ records of financial transactions to understand customer behaviour, optimize services, and inform strategic planning.
- The goal is to **build a dashboard that extracts patterns, segment behaviours, and revenue drivers** that banks use to:
  - Improve personalization
  - Assess customer risk and profitability
  - Refine marketing campaigns
  - Optimize branch and channel performance

------------------
## 2. Problem breakdown
- **Key metrics** are broken down by 3 key aspects:
  - Customer behavior
  - Service Analysis
  - Risk Analysis  
<img width="1129" height="560" alt="image" src="https://github.com/user-attachments/assets/37f7af4b-47b6-43a6-bd6c-1e32f3b801a1" />

- These metrics are sliced and diced by **key dimensions** (as shown below):
<img width="1046" height="240" alt="image" src="https://github.com/user-attachments/assets/88d68157-c2e0-4c7d-b865-403ab12d9afc" />

------------------

## 3. Dashboard breakdown
***3.1. Customer Behavior Overview***
<img width="1472" height="845" alt="image" src="https://github.com/user-attachments/assets/76e63ccb-7f80-4652-b6ec-59c044902b38" />

#### ***Insights in customer segments:***

- In 2024, **middle income segment** accounts for 45% of the transaction value with the **most active branches** are in Murcia (13.6%) and Malaga (13.2%), Spain. Followed by **high income segment** (around 33% of the total value).
- There is a peak in transaction value and quantity 📈:
  - In July 2024 in **middle income**:
    - *%MoM Growth Rate of Total Transaction Value* rises by 16%;
    - *%MoM Growth Rate of active customers* increases by 12%
  - At the end of the year (November, December) 2024 among **high income segment**:
    - *%MoM Growth Rate of Total Transaction Value* rises by 14%;
    - *%MoM Growth Rate of active customers* increases by 13%)
- Meanwhile, there is a drop in transaction quantity and value in February and June.

***3.2 Service Analysis***
<img width="1416" height="792" alt="image" src="https://github.com/user-attachments/assets/f48419a1-aaa6-4006-8183-44b5d68e72d5" />

#### ***Insights in behaviors of customer segments:***
- While most transactions occur in loans, mortgages generate the highest total transaction value.

| Customer Segment | Preferred financial products | Distribution of Recommended Offer | Top Channel Used | Top Transaction Type Used |
| ---------------- | -------------------------------- | --------------------------------- | ---------------- | ------------ |
| Middle Income | Mortgage (Business Package), Loan (Gold) | Mid-tier Savings Booster | Mobile, ATM | Transfer |
| High Income | Mortgage (PLatinum), Loan (Business) | Premium Investment Services | Mobile | Transfer, Withdrawal |
| Low Income | Mortgage (Business), Loan (Business) | Financial Literacy Program Access | Mobile, Online | Deposit, Transfer | 

Consider the preferred financial products of all segments are mortgage and loan. The current recommended offer for middle income segment, which is mid-tier savings booster, is not aligned with their demand. Instead, it is recommended to promote "Personal Loan Cashback Offer".

Low income customers often deposit their money into the bank, thus, a new package "Savings Booster" for this segment can be introduced to boost their engagement.

Mobile, Online and ATM are still the top channels for transfer and withdrawal among all segments. 

***3.3. Risk Analysis***
<img width="1355" height="759" alt="image" src="https://github.com/user-attachments/assets/44957395-f126-45b4-833d-92dfa746b92e" />

#### ***Insights in risk:***
- Middle income takes up for the largest amount of fees among all groups.
- Late payment amount and credit score of middle income group are pretty aligned throughout the year of 2024, following the similar pattern in number of active customers which drops in February and peaks in July).
- Late payment fees are the biggest fee among all segments, which can signify a sign of financial distress.

- By 2025, there is a decrease in number of active customers, which might be an early sign of customer churn that needs more data to deep dive.
-----------------------------
## 4. Recommendations
-  In order to enhance customer retention, product offerings can be optimised to match segment demand, especially for middle and low income segment. Different credit packages regarding payment due and discounts can be adjusted.
-  Banks can also consider promote special offers or campaigns to customers during February and May to June to enhance customer engagement, as these months see decline in number of active customers.
