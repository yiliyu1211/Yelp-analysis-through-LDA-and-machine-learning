# Yelp-analysis-through-LDA-and-machine-learning

This project was held in University of Minnesota master in business analytics program 2019-20 and much thanks to my teammates, Yi Zhu, Boyang Wei, Lin Xu, Xiangke Chen and Yusha Wang.

To analyze the customers' satisfication through comments on Yelp, we used svm predictive model and LDA to capture the hidden topics in positive or negative comments. Also, we built an interactive Tableau dashboard to visualize our results. 

Approach:

1. Quantify the polarity score on sentence level on every comment to have an overall look of the satisfication of every restaurant.

2. Perform TF-IDF methods on words in the comments and apply predictive model (SVM) to unify the different rating standards from different customers.

3. Perform LDA analysis on the true ratings generated from the predictive model and visualize through Tableau dashboard.



The dataset is from: https://www.yelp.com/dataset

Tools used: pySpark, AWS, python, Databrick, Tableau

Check out out demo of the interactive dashboard: [link](https://public.tableau.com/profile/xiangke.chen#!/vizhome/YelpReviewAnalysis_15758570841320/final)

[Imgur](https://i.imgur.com/l05yGjl.png)
