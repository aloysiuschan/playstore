# playstore
The Jupyter notebook contains code to analyze the relationships between Google Play Store app features and app ratings. Data was obtained from https://www.kaggle.com/lava18/google-play-store-apps/home, and contains 10841 observations of Google Play Store apps. The dataset contains variables such as app rating, category, size, price, and number of installations. Before analyzing the data, I correct for obvious data entry errors (e.g. app rating cannot be higher than 5).

My findings are summarised as follows:
1) App ratings follow a left-skewed distribution, with a mean of 4.19 and a standard deviation of 0.53
2) On average, education apps are the highest-rated (4.38), while dating apps are the lowest-rated (3.97)
3) The lowest-rated apps tend to be smaller in size
4) Paid apps tend to have higher ratings than free apps (difference is statistically significant at the 1% level)
5) Higher-rated apps tend to be installed more times than lower-rated apps (difference is statistically significant at the 1% level)
