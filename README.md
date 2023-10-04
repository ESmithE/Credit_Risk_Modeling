# Credit_Risk_Modeling

Lending Club Loan Data

I will focus in consumer Loans, The data set contains all available data for more than 8 hundred thousand  consumer loans issued form 2007 to 2015 by Leanding Club

The dataset contains all available data for more than 800,000 consumer loans issued from 2007 to 2015 by Lending Club: a large US peer-to-peer lending company. There are several different versions of this dataset. We have used a version available on kaggle.com. You can find it here: https://www.kaggle.com/wendykan/lending-club-loan-data/version/1
We divided the data into two periods because we assume that some data are available at the moment when we need to build Expected Loss models, and some data comes from applications after. Later, we investigate whether the applications we have after we built the Probability of Default (PD) model have similar characteristics with the applications we used to build the PD model.

# Methods 
- Credit risk
- Determing relevant predictors
- Preprocessing (cleaning data, missing values)
- Disccrite values
- Continuous data
- Probability of default
- Techniques:
  - Fine classing - slice the information equal size intervals 
  - Coarse classing - slice the information,  no equal intervals
  - Weight of evidence
  - Information Value

# Models used
- Probability of Default (Logistic Regression)
    All of the independent variables have to be categorical. it is much earies to present the model in a simplified form and turn into a Scorecard
- Loss Given Default (Beta regression)
- Exposure At Default (Beta regression)
- Scorecard
- Expected Loss (key strategic metric for bank management)
- Maintain credit risk models

  Note:
  I used the loan status as an flag or indicator
  I will combine 2 or more categories into new
  This Continuous variables (ANUAL INCOME , NUMBER OF CREDIT INQUIRIES IN THE LAST 6 MONTH) be transformed into categorical dummy variables  

# Tech Stack
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-Learn
- GitHub

# Explore

Jupiter








 
