# End-To-End-Data-Analytics-Project_Banking
This project involves a dataset meticulously crafted over several weeks, comprising 1 million randomly generated records distributed across 8 distinct tables. The dataset has been designed to demonstrate a high level of data modeling and management skills, making it an excellent addition to your portfolio. This project not only highlights your ability to work with large volumes of data but also your proficiency in database design, data generation, and manipulation techniques.

# Introduction :

The Czechoslovakia Bank has provided a dataset containing information about its financial activities for the past 5 years. The dataset consists of the following tables:

1. **Account**: This table contains information about the accounts held by the bank's clients. It includes the account ID, the date the account was opened, the associated client ID, and the account type.

2. **Card Table**: This table stores comprehensive details about the bank-issued cards. It includes the following key attributes:
     - **Card ID**: A unique identifier for each card issued by the bank.
     - **Issue Date**: The date on which the card was issued to the customer.
     - **Card Type**: The type of card (e.g., Credit, Debit, Prepaid, etc.).
 

3. **Client Table**: This table contains essential details about the bank’s clients, including:
     - **Client ID**: A unique identifier assigned to each client for tracking and managing their account-related data.
     - **Birthdate**: The client’s date of birth, used for age verification and demographic analysis.
     - **Gender**: The gender of the client, which can be used for personalized services and statistical reporting.
     - **District**: The geographical district or region where the client resides, helping with location-based services and marketing strategies.
 

4. **Disposition Table**: This table captures the relationship between clients and their accounts, providing details about the roles or designations a client may hold in relation to a specific account. Key 
   attributes include:
      - **Disposition ID**: A unique identifier for each disposition record, ensuring traceability and integrity.
      - **Client ID**: The unique identifier for the client associated with the disposition, linking this record to the relevant client in the **Client Table**.
      - **Disposition Type**: The role or relationship type a client holds concerning the account (e.g., **Owner**, **Authorized Person**, **Beneficiary**, etc.).


5. **District**: This table contains information about the various districts in Czechoslovakia. It includes the district ID, the name of the district, and various demographic and economic indicators for the 
   district.
   

7. **Loan Table**: This table holds critical information regarding the loans issued by the bank. It includes the following key attributes:
      - **Loan ID**: A unique identifier for each loan, ensuring individual tracking and management of loan records.
      - **Issue Date**: The date on which the loan was issued to the borrower, which helps track the loan’s term and payment schedule.
      - **Account ID**: The unique identifier of the account associated with the loan, linking the loan record to a specific client or account holder.
      - **Loan Amount**: The total amount of the loan issued, which is essential for financial calculations such as interest, repayment schedules, and loan servicing.


7. **Order Table**: This table stores details about the orders placed by the bank's clients. The key attributes include:
      - **Order ID**: A unique identifier for each order placed, ensuring proper tracking and management of client transactions.
      - **Account ID**: The unique identifier of the account associated with the order, linking the order to a specific client or account holder.
      - **Order Date**: The date on which the order was issued, which helps in managing timelines and tracking order history.
      - **Order Description**: A brief description of the order, providing context about the type of transaction or service requested by the client (e.g., product purchase, service request, etc.).


8. **Transaction**: This table contains information about the transactions made by the bank's clients. It includes the transaction ID, the account ID associated with the transaction, the transaction date, the 
   type of transaction, and the transaction amount.


# Ad-hoc Data Analysis :

The Czechoslovakia Bank wants to analyse its financial data to gain insights and make informed decisions. The bank needs to identify trends, patterns, and potential risks in its financial operations. They also want to explore the possibility of introducing new financial products or services based on their analysis.

The bank has identified the following questions as important for their analysis:

1. What is the demographic profile of the bank's clients and how does it vary across districts?
2. How the banks have performed over the years. Give their detailed analysis year & month-wise.
3. What are the most common types of accounts and how do they differ in terms of usage and profitability?
4. Which types of cards are most frequently used by the bank's clients and what is the overall profitability of the credit card business?
5. What are the major expenses of the bank and how can they be reduced to improve profitability?
6. What is the bank’s loan portfolio and how does it vary across different purposes and client segments?
7. How can the bank improve its customer service and satisfaction levels?
8. Can the bank introduce new financial products or services to attract more customers and increase profitability?

The objective of this analysis is to provide the Czechoslovakia Bank with actionable insights that can help them make informed decisions about their financial operations. The analysis will involve data cleaning, exploratory data analysis, and predictive modelling to identify patterns and trends in the data.




