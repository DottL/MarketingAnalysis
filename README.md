# iFood's Campaign Analysis
![IFood_logo svg](https://github.com/user-attachments/assets/741689c5-f9dc-4a08-841d-1476b086a916)
## Table of Contents
- [Project Background](#project-background)
- [Executive Summary](#executive-summary)
- [Insights Deep-Dive](#insights-deep-dive)
  - [Successful Campaigns](#successful-campaigns)
  - [Campaigns and Deals](#campaigns-and-deals)
  - [Purchase methods](#purchase-methods)
  - [Core Customer Groups](#core-customer-groups)
- [Recommendations](#recommendations)
- [Assumptions and Caveats](#assumptions-and-caveats)

----
# Project Background
iFood specializes in online food ordering and delivery, they were previously based in Colombia and are now operating in Brazil. I will analyze the sample dataset used for their Data Analyst hiring step, found on Kaggle and publicly available on GitHub.

## Executive Summary
In terms of profit, campaigns 1 and 5 were the most successful. Campaign 2 did the worst in both acceptance count and profit. Store-bought items were the most popular throughout all campaigns, followed by web purchases. Our highly valued customers are typically older, higher-income, have no young children, and are either married or together.

## Insights Deep-Dive
### Successful Campaigns
* Campaigns 1 and 5 were the highest in both profit and acceptance count. They were primarily accepted by our highly valued customers.
  * Campaign 2 had little acceptance from our highly valued customers or any customers.
 <div align="center">
  <img src="https://github.com/user-attachments/assets/d2df7d35-0b9a-4017-8733-b22c23778dd5" alt="Profit and Acceptance" />
</div>

### Campaigns and Deals
* Although campaign 3 had a great acceptance count; most of its receivers were mid-valued customers, who also happen to be the highest population for most deals in their purchases.
This behavior explains the profit dip in both campaigns 3 and 4 despite both campaigns having a fairly high acceptance count.
<div align="center">
  <img src="https://github.com/user-attachments/assets/ec00faa8-e57f-4f61-be4a-06bc18aed591" />
</div>


### Purchase Methods
* Most items were bought in stores and on the web.
  * For web purchases, it's seen that our higher-valued customers have fewer web visits per month than their counterparts.
 <div align="center">
  <img src="https://github.com/user-attachments/assets/7438f7fb-7bb6-4669-8b21-2070382281a2" alt="Purchase Methods and Web Visits" />
</div>

### Core Customer Groups
* Our highly valued customers are on average 53 years in age with an income mean of 70k. Most are in a relationship and have little to no children
As opposed to our lower valued customers with a lower income and more children.
 <div align="center">
  <img src="https://github.com/user-attachments/assets/41952bd3-06cf-40cd-a863-8ebc370b4503" />
</div>
 <div align="center">
  <img src="https://github.com/user-attachments/assets/4c9c36a8-6317-43c0-a973-8ee92906afb4" />
</div>

## Recommendations
* **Reconsider the number of deals or the deal values distributed**;
  * Although deals increase the acceptance rate, it decreases our general profit. To ensure success, we should appeal to our higher-valued customer groups. Which are the middle-aged, higher-income, and childless populations.
* **Broaden our connections with additional stores**;
  * Expanding our reach can only improve our business since stores are the primary purchase method for most of our customers.
* **Improve web traffic and interactions**;
  * The less time spent on our website, the more likely they are to spend. This can be reviewing the website’s layout, load speed, user-friendliness, and the website’s conversion funnel.

## Assumptions and Caveats
* **Little to no complaints**; within the last two years, there were only a total of 20 complaints. This can be a good sign but it's suspicious.
* **Revenue and contact cost columns**; excluded due to ambiguity; Columns Z_Revenue and Z_CostContact are only one value, 11 and 3 respectively. 



