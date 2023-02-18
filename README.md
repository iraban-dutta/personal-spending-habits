# personal-spending-habits
In this project we have tried to study our spending habits from personal bank statements.  

## Project Highlights:
  - Data cleaning:
    - The data we have used is from our own bak statements.
    - This raw data required a lot of cleaning before we could perform the exploratory analysis.
  - EDA on the cleaned data:
    - Addressing the problem statement and also looking for interesting facts about the data.
  - Tableau Dashboard for effective information consumption:
    - Link to dashboard: https://public.tableau.com/app/profile/iraban.dutta/viz/SpendingHabits2020-2022/SpendingHabitsDashboard
  ![tableau_dash_snap](https://user-images.githubusercontent.com/108816719/219885109-e5085309-0eff-4464-9ad8-0f604c3e4f3b.PNG)




## Answering the following questions using EDA:
For this project we have analysed the transactions from a single bank A/C (which we use for making our daily payments).


- **Overview:**
  - Number(%-split) of Debit vs Credit transactions:  
    ![trnsc_debit_vs_credit](https://user-images.githubusercontent.com/108816719/219885146-562fb81b-5bbd-400b-b3e1-675af9d6c1af.png)
  - Number(%-split) of transactions across different transaction modes & categories:  
    ![trnsc_across_modes](https://user-images.githubusercontent.com/108816719/219885206-214e92ac-aa1b-4a6b-a979-c67920fbcdeb.png)
    ![trnsc_across_categories](https://user-images.githubusercontent.com/108816719/219885211-25d92ab1-d166-47c5-819e-fa2ded9b9e25.png)


- **Debit transactions:**
  - Which payment mode is used most frequently?  
    ![debitTrnsc_across_modes](https://user-images.githubusercontent.com/108816719/219885250-494f6fa4-089c-45c5-90ae-70282ddbe7ea.png)
  - Which category records:
    - the highest number of transactions?
    - the maximum total amount debited across all transactions?  
      ![debitTrnsc_across_categories](https://user-images.githubusercontent.com/108816719/219885289-7bafdc6e-4980-4c96-b014-d5b4787ad852.png)
  - Do we tend to use a particular payment mode for a particular category?  
    ![debitTrnsc_across_categories_modes](https://user-images.githubusercontent.com/108816719/219885268-6ea78cb5-11fb-4a16-b5bb-99555fad43ad.png)


- **Temporal trend of debit transactios:**
  - YoY spending:  
    ![temporal_yoy](https://user-images.githubusercontent.com/108816719/219887811-683fda2c-2715-4096-8ff7-8c450c0d43c6.png)
  - Classifying categories into daily needs and daily wants (Needs vs Wants: YoY spending):  
    ![temporal_needs_wants_YoY](https://user-images.githubusercontent.com/108816719/219888501-2706c05f-15ae-4ff4-bceb-fc6f93a1b3a2.png)
    
  - ***Needs:***
    - Which categories in daily needs have the highest expenditure?  
      ![temporal_highValueNeeds](https://user-images.githubusercontent.com/108816719/219888690-1c84217d-fe77-47a6-9531-322cf0af4c05.png)
    - What are the different insurance products we own and how much are we spending on them?  
      ![temporal_insurance](https://user-images.githubusercontent.com/108816719/219889633-86e5c93b-759f-4828-8b05-890f8e7748ab.png)
    - What modes of public transport do we use across the years?  
      ![temporal_publicTransport](https://user-images.githubusercontent.com/108816719/219889770-a4fa5489-cb87-4e00-8eaa-b0497e8a9073.png)
    - What is the median number of days we wait before getting successive haircuts? 
      - We observe that it is 29.5 days.
      ![temporal_haircut](https://user-images.githubusercontent.com/108816719/219889891-25b37825-84ac-42da-8309-947c98af7aef.png)

  - ***Wants:***
    - YoY spending on wants:  
      ![temporal_wants_YoY](https://user-images.githubusercontent.com/108816719/219890456-c1281ec4-09d6-4c1d-ba53-9b259ab20964.png)
    - Which categories in daily wants have the highest expenditure?  
      ![temporal_highValueWants](https://user-images.githubusercontent.com/108816719/219890519-2e2787ce-875c-49b7-970e-a0df29d9afcf.png)
    - Do we tend to spend more on our wants across specific months in a year? Does the festival season in India have any impact on this?  
      ![temporal_wants_monthlyTrend](https://user-images.githubusercontent.com/108816719/219890588-56651506-3396-4916-8905-2e49fc8105a5.png)
    - Which are the our popular retail outlets?  
      ![temporal_retail](https://user-images.githubusercontent.com/108816719/219890665-80f183e2-ac38-4247-98d5-2a775a9b62cb.png)
    - How much did we spend on the different vacations we took in the last 2.5years?  
      ![temporal_vacations](https://user-images.githubusercontent.com/108816719/219890734-eb5f0851-6b5c-4638-b49b-59a9493e4bb2.png)
    - How frequently in a week do we order food or eat outside?
      - We observe that it is 4 days.
      ![temporal_eatout](https://user-images.githubusercontent.com/108816719/219890821-b7a9bcc1-47e5-4226-bed8-1ea98b60d832.png)
    - What is maximum amount we spent in a single day eating outside? Is this an outlier or do we generally spend around this maximum amount?  
      - Maximum amount spent in 1 day on eating outside: 15337
      - However our median amount spent on eating outside: 666.475. Thus clearly the maximum amount is an oulier as also suggested by the graph below.
      ![temporal_eatout_1day](https://user-images.githubusercontent.com/108816719/219891009-5657b7f1-5412-41bc-aa92-1de2af6f8fca.png)

    
## Tableau Dashboard:
- The dasboard summarizes our spending habits across:
  - Year.
  - Transaction modes.
  - Transaction categories.
  - Total number of transactions, total amount spent, median, maximum and minimum amount are also shown.
- Filter action:
  - We can individually filter on the basis of year, transaction mode, transaction category or any of these combinations and the dashboard reacts accordingly.
  - We show a needs vs wants split for our selection.
  - We can also see the top-5 beneficiaries for our selection.
    
    
    
