# Kickstarter Analysis

## Table of Content
1. [Project Motivation](#project-motivation)
2. [Installation](#installation)
3. [Findings](#findings)
4. [Licensing, Authors & Acknowledgements](#licensing-authors--acknowledgements)

## Project Motivation
Kickstarter is a platform that helps people to raise funds for their projects. Each project will have a 'goal' that represents the amount of money that the product owner is hoping to raise. The people who contributed their money into the project are called 'backers'.

This project aims to provide insights into the different factors that can affect the success of a Kickstarter project. With this analysis, I hope that future fundraisers, or even backers, can be more discerning about the project elements to take into account to boost the chances of getting successful project.

## Installation
The code should using Python version 3.0 and above. The additional libraries required to execute the code can be installed by running `pip install -r requirements.txt`

## Findings Summary

_Riskiest Category_
- The riskiest category is ‘Technology’. Not only does it require a lot of funds in the first place, but it also has the lowest success rate across all main categories.
- ‘Journalism’ & ‘Crafts’ also have low success rates even though the amount of funds required to build the project is relatively low. When these projects failed, the amount of loss tends to be a lot lesser than the loss of Technology projects.
- From the initial analysis, ‘Design’ seems to be pretty popular among backers and it has the highest median amount pledged. However, the goal that is set for Design projects tends to be high, which makes it more challenging for it to be successful.

_Safest Category_
- The safest category to go for is ‘Dance’, followed by ‘Theater’ and ‘Comics’. These projects do not require a lot of fixed costs to start and have the highest success rates.
- If product owners can reduce the cost associated with Design projects significantly, then it can be a good category to launch your product.
Ideal Duration
- Duration does not seem to affect the success of a project much. Setting a longer duration does not necessarily increase the amount pledged and the number of backers.
- Based on the analysis, the ideal duration is around 30–60 days, where it can attract the highest number of backers & generated a good amount of money pledged.

_Ideal Duration_
- Duration does not seem to affect the success of a project much. Setting a longer duration does not necessarily increase the amount pledged and the number of backers.
- Based on the analysis, the ideal duration is around 30–60 days, where it can attract the highest number of backers & generated a good amount of money pledged.

Please check out this [Medium blog post](https://lsndjie.medium.com/kickstarter-analysis-understanding-successful-campaigns-297400ba5cda) for the full write-up!

## Licensing, Authors & Acknowledgements
Credits to Mickaël Mouillé for providing the data. Dataset can be found here on [Kaggle](https://www.kaggle.com/kemical/kickstarter-projects).
