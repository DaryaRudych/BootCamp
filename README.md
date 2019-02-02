# KickStarter Analysis (Excel)

## Background
Over two billion dollars have been raised using the massively successful crowdfunding service, Kickstarter, but not every project has found success. Of the over 300,000 projects launched on Kickstarter, only a third have made it through the funding process with a positive outcome.

Since getting funded on Kickstarter requires meeting or exceeding the project's initial goal, many organizations spend months looking through past projects in an attempt to discover some trick to finding success. In this project, I will organize and analyze a database of four thousand past projects in order to uncover any hidden trends.

## Trends & Observations
![alt text](https://github.com/DaryaRudych/KiskStarter-Analysis/blob/master/CampStatusVsCat.png)

1. Given the provided data, we can conclude that most of Kickstarter projects (70 %) fall under four categories, which are “theater”, “music”, “film&video”, and “technology”.  Projects in “theatre”,“music”, and “film&video”, on average, succeed more often than fail. Meanwhile, campaigns in the field of technology seem to have roughly equal chances to fail or succeed. However, if we equate canceled campaigns to failed ones, then it seems like campaigns in technology tend to fail rather than succeed. 

![alt text] (https://github.com/DaryaRudych/KiskStarter-Analysis/blob/master/CampStatusVsSubCat.png)

2. Campaigns in sub-category “plays” have the highest chance of succeeding (65%). Then come projects categorized as “rock”, “documentary”, “hardware”, and “indie rock”. Campaigns in “science fiction”, “art books”, and “audio” have always been canceled. Projects in “web”, “animation”, “gadgets”, “children’s books”, “drama”, “fiction”, “jazz”, “mobile games”, “people”, “places”, and “video games” have 100% failure rate. 

![alt text] (https://github.com/DaryaRudych/KiskStarter-Analysis/blob/master/StartVsOutcome.png)

3. January is the start month of most of the fundraising campaigns. However, roughly 50% of them ended in success. Campaigns started in February-May on average have 60% chance of ending in success. Out of these 4 months, projects started in May are most likely to succeed. Projects started in November and July are most likely to be cancelled. Overall, because the probability margins for success/failure of the campaigns are fairly small, it is hard to evaluate how launch month will affect the campaign’s outcome. In general, the given data seems to support the fact that Dec-Jan being the biggest holiday spending season for most people in the West is consequently a bad time to start a Kickstarter campaign as people are spending their money elsewhere. 

## Limitations
1.The status “cancelled” is somewhat problematic as there is not any other data that would help us differentiate cancelled projects from projects that failed. While the cancelled projects in most cases are underfunded, there were a few that reached their target budget or were even overfunded. This leads to questions as to how we should define the status of the campaign. 

2. The given dataset is not normalized (i.e. is not on the same scale). For instance, to come up with the probabilities of the campaign failing or succeeding given a certain start time, I had to do additional calculations to be able to compare one month to another. While the charts produce a visualization that helps us eyeball which campaign categories, on average, fail and/or succeed, these estimates are not very reliable. In addition, the column “percent funded” For example, according to Fig. 1, projects in technology seem to have a higher likelihood of failing or being cancelled than ending in success. However, this chart disregards the fact that projects in technology are also those among the most overfunded projects. This produces mixed conclusions. 




