# Business Understanding

## Context
The banking industry is highly competitive, with fixed-term deposits being a popular product among customers. Fixed-term deposits require customers to deposit a certain amount of money, which can only be withdrawn after a specified period, in return for a fixed interest rate. To stay competitive, banks must continuously innovate to retain and attract new customers, often through targeted marketing campaigns.

**Electric Bank** has been running a series of telemarketing campaigns aimed at encouraging customers to subscribe to term deposits. However, these campaigns have not yielded the desired results. Despite extensive efforts, a significant number of customers are declining to make deposits.

Out of 41,188 customers contacted, only 4,640 have subscribed to a term deposit, resulting in a conversion rate of approximately 11.27%. Each telemarketing call costs the bank 50 euros, leading to a total telemarketing expenditure of 2,059,400 euros. This substantial cost, coupled with the low conversion rate, indicates that the current telemarketing strategy is not as effective as it could be. The bank is incurring high expenses without achieving the desired return on investment.

Target :

0 : Not subscribe term deposit

1 : Subscribe term deposit

## Problem Statement 

The primary challenge is to develop a machine learning model that can accurately predict whether a customer is likely to subscribe to a term deposit. By doing so, Electric Bank can focus its telemarketing efforts on high-potential customers, thereby increasing the conversion rate and reducing overall telemarketing costs

- How to predict the likelihood of a customer subscribing to a term deposit so we can increase the conversion rate and minimize telemarketing costs.
- What customers should we focus our telemarketing efforts on in order to increase the conversion rate and reduce telemarketing costs?

## Goals

The main objectives of this project are:

**Increase Conversion Rate**: Identify clients who are more likely to subscribe to a term deposit, leading to a higher conversion rate.
**Lower Telemarketing Costs**: Reduce the number of unnecessary calls by focusing on clients who are more likely to convert, thereby lowering the overall telemarketing costs.

## Evaluation Metrics

The key evaluation metric for this project is precision. Precision is chosen because the cost of false positives (predicting that a client will subscribe when they actually won’t) is high. With precision, we can focus on ensuring that the clients we predict as likely to subscribe are indeed the ones who will do so, which directly supports the goal of reducing unnecessary telemarketing efforts.

## Stakeholder

The primary stakeholder for this project is the Director of Data Science in **Electric Bank**.
