## Overview of Project
Louise’s play Fever came close to its Kickstarter fundraising goal in a short amount of time. Now, she wants to know how different Kickstarter campaigns fared in relation to their launch dates and their funding goals.

### Purpose
Using data from Kickstarter an analysis will be made for Louise by visualizing the different kickstarter campaign outcomes based on their launch dates and their funding goals.

## Analysis and Challenges

Two different analysis of play outcomes are made.  They address the temporal variable of launch date and the fiscal variable of financial goal.




### Analysis of Outcomes Based on Launch Date

An analysis of launch date elucidates the effects of timing on the success of the campaign.

![Theater_Outcomes _vs_Launch](https://user-images.githubusercontent.com/16930677/116925751-76f1a680-ac0e-11eb-811a-74f874331c03.png)

### Analysis of Outcomes Based on Goals

An analysis of financial fundraising goals elucidates the effects of fiscal requirements on the success of the campaign

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/16930677/116925832-912b8480-ac0e-11eb-99e8-b9789ce812a6.png)

### Challenges and Difficulties Encountered

None. The Kickstarter dataset required little cleaning and was ready for analysis. We were fortunate the dataset was well populated with play campaigns (~1400 plays).  Therefore we had a large enough sample size to eliminate small sampling biases. Had there been 10 plays, our analysis would likely have significant error. 

## Results

- Decemeber is the worst month for launching a theater kickstarter campaign with the number of successful campaigns roughly equal to the number of failed campaigns.
- May is the best month for launching a theater kickstarter campaign with the number of successful campaigns roughly 2.15x the number of failed campaigns

- Setting a financial fundraising goal lower than 1500 improves your likelihood of success for success.

- Some limitations of the data set are the non-normalcy (right skewed) of the data when filtering by financial fundraising goal amount.  This decrease our sample size for campaigns above $1500.

- Other vairables not studied are country of origin, percentage by backer, and year over year trends.
