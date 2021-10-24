# Kickstarting with Excel

## Overview of Project

### Purpose
The goal of this review is to provide Louise information on Kickstarter campaigns that were similar to her own. This is to allow for a deeper understanding of results about fundraising goals and launch dates.

Source Data: [Kickstarter_Challenge.xlsx](https://github.com/HopkinsKV/kickstarter-analysis/files/7406152/Kickstarter_Challenge.xlsx)


## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
October and December have a higher instance of failed campaigns. January has a much higher occurrence of canceled campaigns. May has the highest successful campaigns by far, followed by June and July.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/91762315/138610627-8a8420e4-d46a-4cad-a92b-a6b11ec7c7f7.png)

### Analysis of Outcomes Based on Goals
Goals higher than $20,000 were more likely to fail than succeed. Goals lower than $15,000 were more likely to succeed.
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/91762315/138610624-e344a7c5-53e3-4a63-81e5-a51ec3dbc1f6.png)

### Challenges and Difficulties Encountered

One challenge is related to the idea of ‘Greater Than’. The requested documentation indicates that the final bracket is only to include items greater than $50,000. However, there are data points that are equal to this amount. For clarity, items equal to $50,000 were included in this data set as well.

It is advisable to review the launch date data based on percentages instead of individual points. This allows a clearer understanding of the relational aspect between success, failure, and cancellation. This information can be clearly depicted as a graph.

Additional clarity could be obtained by filtering the data further to specify by location, as there are vast differences between the success rates by country. A series of charts can be presented to show these differences.

A more dialed in set of data may assist in setting the final goals for this launch. This could be obtained by obtaining additional data on the type of play, the target audience, or the language the play is presented in. Lacking these more specific points limits scope of the data.

Additional review should be completed to ensure accuracy of the data provided, as some blurbs indicate there are more accurate subcategories that should have been chosen for the campaign.


## Results

- It is not advisable to launch a campaign in October or December, due to the higher rate of failed campaigns. 
It is also not advisable to launch in January, due to a much higher rate of canceled campaigns.
May and June are the best months to launch a campaign. The success rate is highest during these months.

- Campaigns with lower goals were more successful overall. The clear differentiator lies at the $15,000-$19,999 point. Goals above that are less likely to succeed, whereas goals less than that are more likely to succeed.

- Some limitations of the dataset are detail and accuracy. Additional detailed categories will assist in gleaning a better understanding. As noted, some blurbs do not line up with the subcategories selected.

- We could create a series of charts listing the data breakdown by location. We could create a graph to show the percentages of outcomes based on launch date.
