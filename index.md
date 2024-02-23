
**Yes, I am aware that this public github page should be linked to a private repo containing our code. However, we have no code so far and I am still waiting on student verification. Once this is done, I will fix everything. (Following the results on this ed discussion post: https://edstem.org/us/courses/50208/discussion/4394357)**


# Project Proposal - Predicting the Outcome of NBA Games

## Introduction/Background

As many sports bettors understand, successful betting requires a combination of luck and knowledge. While playing games of chance, knowing the odds as best one can (and hopefully better than the others who bet with you) will likely lead to positive returns. So, while luck remains beyond our control, enhancing our knowledge of the odds is a valuable proposition. In the NBA regular season, 30 teams each play 82 games, for a total of 1230 games. In the postseason, the playoffs are an elimination tournament consisting of 15 best-of-seven matchups, leading to a maximum of 105 playoff games and a minimum of 60. Each game involves a number of quantifiable events and statistics that together can indicate the likely outcome. So in total, a gambler has at least 1290 opportunities to make money betting on the outcome of NBA games in a year. 

The dataset that we intend to use is a collection of games played between teams from 2004 onwards.


### Dataset:
https://www.kaggle.com/code/nathanlauga/nba-games-eda-let-s-dive-into-the-data


## Problem Definition

Given an upcoming NBA matchup between two teams, how is a person to pick a likely winner? When there’s a superteam, like the 2016 - 2019 Golden State Warriors, in the match, a regular person could be assumed to be right more than half of the time (if they pick the superteam). But what about when the matchup is more even? Our project hopes to answer the question of which NBA team will win a matchup with as much accuracy as possible.

A more interesting problem, beyond just the binary win-lose, is: can a person predict the final scores in a game with reasonable accuracy? This is also the subject of many bets on bookkeeping websites, and so is another opportunity for enterprising gamblers to make money.



## Methods

Many of the features present in the dataset may have limited relevance, such as the arena capacity, or may not be filled in for the entire dataset, such as birth year. To determine the relevancy of each feature, we will likely use Principal Component Analysis. [1]

As this is a classification problem with a provided ground truth, supervised learning methods seem appropriate. We intend to make use of logistic regression, neural networks, and SVMs [2][3].


## Potential Results and Discussion

Our objective is to build a model that will take in the statistics of two NBA teams and their players to predict both the winner of a basketball match between them and the final scores of the two teams. Some metrics by which our result can be judged are precision, recall, and accuracy. Other projects similar to this have accuracy rates between 60% and 85%, so our goal is to reach 80% accuracy. 

## References 

[1] C. Fan et al, “A Review on Data Preprocessing Techniques Toward Efficient and Reliable Knowledge Discovery From Building Operational Data”, Frontiers in    Energy Research, March, 2021[Online]. Available: https://www.frontiersin.org/articles/10.3389/fenrg.2021.652801/full [Accessed 22 Feb 2024]

[2] K. Zhao, C. Du, and G. Tan, “Enhancing Basketball Game Outcome Prediction through Fused Graph Convolutional Networks and Random Forest Algorithm”,  
  National Library of Medicine, May, 2023 [Online]. Available: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10217531/  [Accessed 22 Feb 2024]

[3] C. Lu, T. Lee, C. Wang, and W. Chen, “Improving Sports Outcome Prediction Process Using Integrating Adaptive Weighted Features and Machine Learning 

  Techniques”, Multidisciplinary Digital Publishing Institute, September, 2021 [Online]. Available: https://www.mdpi.com/2227-9717/9/9/1563 [Accessed 22 Feb
  2024]


## Contribution Table

![Contribution Table](https://github.com/rossydang/NBA-Predictor-GithubPage/blob/main/assets/images/contribution_table.png)

## Gantt Chart
![Gantt](https://github.com/rossydang/NBA-Predictor-GithubPage/blob/main/assets/images/Gantt.png)






