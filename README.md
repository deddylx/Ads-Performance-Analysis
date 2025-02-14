# Ads Performance Analysis

Company ABC ran 5 types of ads along Januari-April 2017. After running the campaign, the managers realize needed ad improvement and efficiency. The objective is the company needs an analysis to find **the top 2 best-performing ads** in the scope of best brand awareness ad and the highest traffic generation ad objectives. He ask you to provide a simple marketing dashboard to help him to **assess** the campaign performance and **create** an actionable plan.

## Metrics and Dimensions
### Metrics
- **Click:** Number of click per day
- **Ad Recall:** Number of people who recall our ad
- **Ad Recall Lift:** Number of Ad Recall compared to number of Reach 
- **Click Through Rate (CTR):** Number of clicks compared to number of impressions
- **Marketing Cost:** Marketing cost spent per day
- **Cost Per Mile (CPM):** Marketing Cost per 1000 impressions
- **Cost Per Click (CPC):** Marketing cost for each click
### Dimensions
- **Datetime:** From Januari 2017 - April 2017
- **Ad type:** Ad type A, B, C, D, and E


## Insight Summary
Our analysis will encompass two primary scopes: brand awareness and traffic generation. Within the brand awareness domain, our focus will be on key performance indicators such as **Ad Recall Lift** and **Cost Per Mile**, which provide insights into campaign reach and audience retention. Meanwhile, for the traffic generation scope, we will emphasize performance metrics like **Click Through Rate** and **Cost Per Click**, enabling a deeper evaluation of engagement efficiency and cost-effectiveness.


**Ad Recall Lift**
- Among all ad categories, **ad type E** emerged as the top performer, achieving an impressive **14.94%**, significantly surpassing the overall average of **8.93%**.
- In contrast, **ad type D** recorded the lowest performance with a value of **5.26%**, marking a notable underperformance relative to other types.
- Over the course of the campaign, the peak performance was observed in **February 2017**, where the metric reached its highest point at **9.42%**.

**Cost Per Mile**
- Among all ad types, **ad type D** recorded the lowest cost per mille (CPM) at **$38.59**, though it also suffered from the weakest ad recall lift performance.
- Meanwhile, **ad type E** ranked second in CPM at **$38.93**, demonstrating only a marginal difference in cost, yet achieving the highest average ad recall lift, highlighting its superior effectiveness.

**Click Through Rate**
- The average click-through rate (CTR) across all ad types stood at **3.74%**, with the highest monthly performance observed in **March 2017**, reaching **3.90%**.
- Among individual ad types, **ad type A** delivered the strongest CTR at **4.97%**, outperforming its peers.
- Conversely, **ad type D** recorded the lowest CTR at **2.76%**, marking it as the least effective in driving engagement.

**Cost Per Click**
- Across all ad types, **ad types A and B** achieved the lowest cost per click (CPC) at **$1.00**, highlighting their cost efficiency. Notably, ad type A also delivered the highest click-through rate (CTR), reinforcing its strong performance.
- In contrast, **ad type D** recorded the highest CPC at **$1.61**, indicating a relatively higher cost to drive user engagement.

## Recommendations
**1. Focus on Ad Type E for Brand Awareness Campaigns**
- With the highest ad recall lift (14.94%) and a competitive CPM ($38.93), ad type E demonstrates a strong ability to reach and retain audience attention. It should be prioritized for campaigns aimed at maximizing brand awareness.
- Consider reallocating a higher budget to ad type E to optimize reach and audience impact.

**2. Leverage Ad Type A for Traffic Generation Goals**
- Ad type A leads in CTR (4.97%) and achieves the lowest CPC ($1.00), making it the most cost-effective choice for driving traffic to the website or landing pages.
- Increase investment in ad type A for traffic generation campaigns to maximize engagement at a minimal cost.

**3. Reassess the Effectiveness of Ad Type D**
- Ad type D underperforms across multiple metrics, including the lowest ad recall lift (5.26%), CTR (2.76%), and the highest CPC ($1.61).
- Evaluate the creative, targeting, or placement strategy for ad type D to identify areas for improvement. Alternatively, consider reducing its budget allocation until its performance improves.

## Dashboard
The dashboard can be found in Tableau Public [here](https://public.tableau.com/views/AdPerformanceDashboard_17326604930840/Dashboard1?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link). This dashboard focuses on value comparison among ad types in brand awareness and traffic generations metrics and enables users to filter by the month the campaign ran.


![image](https://github.com/user-attachments/assets/e0fb1ad6-d000-47fe-ac95-03d29bdfe047)
