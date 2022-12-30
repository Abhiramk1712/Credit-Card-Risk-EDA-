# Credit_Card_Risk (EDA)

Tο analyse data οn lοans and find pattern that predicts οf client having difficulty οf payment in the future

There are 2 types οf risks assοciated while prοviding lοan tο a client
    1. If the lοan is nοt prοvided tο the custοmers whο can pay back then it will be lοss fοr the cοmpany
    2. If the lοan is prοvided tο the custοmer whο can nοt pay then alsο it will be the lοss fοr the cοmpany

Business Requirement:
Derive data-driven, buiness-driven, insight-driven, analysis on what type of customers are prone to have payment difficulties and which sector of clients should be targeted.

Case Study Summary

- Chances of client havind payment difficulty

-> All the below variables were established in analysis of Application dataframe as leading to default. Checked these against the Approved loans which have defaults, and it proves to be correct

-> Medium income

-> 25-35 years olds, followed by 35-45 years age group

-> Male

-> Unemployed

-> Labourers, Salesman, Drivers

-> Own House - No

-> Other IMPORTANT Factors to be considered

-> No of Bureau Hits in last week. Month etc – zero hits is good

-> Amount income not correspondingly equivalent to Good Bought – Income 'Low' and 'High' is a concern

-> Previous applications with Refused, Cancelled, Unused loans also have default which is a matter of concern.

-> This indicates that the financial company had Refused/Cancelled previous application but has approved the current and is facing default on these.

-> Credible Applications refused

-> Unused applications have lower loan amount. Is this the reason for no usage?

-> Female applicants should be given extra weightage as defaults are lesser.

-> Students and Business mean have no problem in repayment of the loan

-> Previous applications with Refused, Cancelled, Unused loans also have cases where payments are coming on time in current application. This indicates that possibly wrong decisions were done in those cases.
