# Predictive-modelling-on-Nigeria-Bank-Campaign-Subscriptions
The dataset contains information about marketing campaigns that were conducted via phone calls from a Nigerian banking institution to their clients.
The purpose of these campaigns is to prompt their clients to subscribe to a specific financial product of the bank (term deposit). 
After each call was conducted, the client had to inform the institution about their intention of either subscribing to the product (indicating a successful campaign) or not (unsuccessful campaign). 

### I found patterns and built predictive model on this dataset with the aim of forecasting the percentage of potential customers for the financial products of the bank.

## Content: 
The predictor variables (features) contained in the dataset can be divided into the following five sections:

#### 1. Variables that describing attributes related directly to the client:

age

job : type of job (e.g. 'admin', 'technician', 'unemployed', etc)

marital: marital status ('married', 'single', 'divorced', 'unknown')

education: level of education ('basic.4y', 'high.school', 'basic.6y', 'basic.9y','professional.course', 'unknown','university.degree','illiterate')

default: if the client has credit in default ('no', 'unknown', 'yes')

housing: if the client has housing a loan ('no', 'unknown', 'yes')

loan: if the client has a personal loan ? ('no', 'unknown', 'yes')

#### 2. Variables related to the last contact of the current campaign:

contact: type of communication ('telephone', 'cellular')

month: month of last contact

dayofweek: day of last contact

duration: call duration (in seconds)

#### 3. Other variables related to the campaign(s):

campaign: number of contacts performed during this campaign and for this client

pdays: number of days passed by after the client was last contacted from a previous campaign

previous: number of contacts performed before this campaign and for this client

poutcome: outcome of previous marketing campaign ('nonexistent', 'failure', 'success')

#### 4. Socioeconomic variables:

emp_var_rate: employment variation rate - quarterly indicator

cons_price_idx: consumer price index - monthly indicator

cons_conf_idx: consumer confidence index - monthly indicator

euribor3m: euribor 3 month rate - daily indicator

nr_employed: number of employees - quarterly indicator
