# Kickstarter-analysis

## Overview of Project
The project aims to analyze how different campaigns fared, in relation to their launch dates and funding goals.
### Purpose
To create statistically based written and visual deliverables that Louise can compare against her fundraising campaign for *Fever*.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The month with the highest Grand Total of plays launched was the month of May. May also had the highest number of Succesful plays. June had the second highest Grand Total and Succesful plays. June also had less Failed plays, though the difference was very small. Very few projects are cancelled.

### Analysis of Outcomes Based on Goals
Projects with goals of less than $5000 had the highest success rates of +70%. The next highest success rates were for projects between $35000 to $44999, but the Total Projects for these goals were exponentially lower. Projects with goals between $1000 to $4999 occured the most frequently, nearly twice as often as the next most common goal. No plays are cancelled.
### Challenges and Difficulties Encountered
#### Challenge 1:
Creating the *Outcomes Based on Goal* table and graph proved to be difficult. There was a disconnect between the understanding of notation from the human perspective compared to Excel. It was easy to forget how precise Excel was, and this resulted in confusion when verifying the values for the table as it took a while to realize that 1000 is not less than 1000.
#### Challenge 2:
It is difficult to have confidence in one's formulas when dealing with data sets of this size since there is no quick way to verify if the values being generated are accurate. Using **Challenge 1** as an example, the intial formula returned a questionable value. The raw data was, therefore, manually reorganized in order to validate the formula being used. Unfortunately, this meant manipulating a signifcicant amount of data on screen, and the computer had difficulties displaying it - resulting in a large number of freezes and delays.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
#### Conclusion 1:
The best time to launch a project would be either in May or June. These months saw both the highest number of projects launching as well as the highest success rates. This means that many in the industry recognize this time as ideal to launch and/or there are more potential backers during this time frame.
#### Conclusion 2:
The *Theatre Outcomes Based on Launch Date* graph indicates that the success:failure ratio is fairly consistent outside of the April to August time frame - failed projects are about half the number of successful projects. The exceptions to this rule are October and December. Therefore, if for some reason, Louise would want to launch a play outside of the obvious "high season", she should at the very least not launch a project in October or December.

#### Figure 1. Theatre Outcomes vs Launch
![Theatre_Outcomes_vs_Launch](https://github.com/jdfiel/An-Analysis-of-Kickstarter-Campains/blob/main/Resources/Theater_Outcomes_vs_Launch.png)

- What can you conclude about the Outcomes based on Goals?

Projects under Goal 1000 to 4999 are the safest to launch, according to the data. Statistically speaking, the Goal 1000 to 4999 success rate of 73% is more reliable than the 76% of Goal Less Than 1000 due to the fact that the sample pool is larger. Thus, even if the 76% is larger, greater confidence can be placed in the 73%. By the same logic, the next highest success rates of 67% cannot be trusted due to the nigh insignifcant sample size.

#### Figure 2. Outcomes vs Goals
![Outcomes_vs_Goals]()

- What are some limitations of this dataset?

The most notable limitaion of this dataset is the fact that the sample sizes for various outcomes are not consistent. It is difficult to discern if the 45000 to 49999 Goal project failed because all projects of that goal will fail or if it simply occurred for this project. This limitation means that we cannot validate any conclusion using stricly numerical approaches to support our arguments as the data can be extremely skewed depending on both the sample size and the sample itself. Another issue is that the currency is not standardized. We are comparing different monetary values - where, $5 USD may have more or less purchasing power than $5 of another currency. This means that, even when comparing successful projects from different companies (currencies) that both recieved $x in pledges, the data will be skewed as one of them will be misrepresented.

- What are some other possible tables and/or graphs that we could create?

Outcomes Based on Duration of Fundraiser

Outcome Based on Play Genre

Outcome Based on Backers
