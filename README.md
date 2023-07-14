# Freedom Debt Relief - Marketing Campaign Analysis

<img src="https://media.giphy.com/media/JrXas5ecb4FkwbFpIE/giphy.gif"  width="300" height="200"/>

### Who is Freedom?

+ Freedom Debt Relief is a company that specializes in debt settlement services.
+ They aim to help individuals and families struggling with unmanageable debt by negotiating with creditors on their behalf to reduce the total amount owed.

### What is their purpose?

+ By working with Freedom Debt Relief, individuals may be able to alleviate their financial burden and work towards becoming debt-free.

### Purpose of this Project

+ Freedom has run a recent Marketing campaign promoting their value propositon
+ The total cost of this campagin was $5 million
+ There are five months of data provided, with the campaign occurring on the third month
+ It is now our turn to present to Marketing, Sales & Operations whether this campaign was successful or not

### This notebook will contain..

+ Data exploration and a quantitative assessment of the campaign's performance
  - Outlining which metrics were chosen and why
  - Recommendations for company strategy to improve future campaign performance
 
### Data Description
#### client_data.csv: You will find data specific to fictional clients

+ client_id: Randomly generated unique surrogate identifier for a client
+ client_geographical_region: Client geographical location in relation to U.S. Census definitions
+ client_residence_status: Client residence status in relation to whether they rent or own
+ client_age: Client age in relation to date of birth

#### deposit_data.csv: You will find data specific to the client deposit behavior

+ client_id: Randomly generated unique surrogate identifier for a client
+ deposit_type: Delineates whether a client deposit is the scheduled record or actual record
+ deposit_amount: Client deposit amount to the dedicated bank account with Freedom
+ deposit_cadence: Timing and pattern of client deposit activity
+ deposit_date: Deposit date for deposit type

#### calendar_data.csv: This is a calendar reference table

+ gregorian_date: This date aligns with the Gregorian calendar
+ month_name: These are the designated months in the case study
  - Month 1 and 2 are pre-campaign
  - Month 3 is the campaign
  - Month 4 and 5 are post-campaign
