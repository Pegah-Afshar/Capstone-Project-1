Google Play Store Apps Proposal
By: Pegah Afsharlar


Goal: The Play Store apps data has enormous potential to drive app-making businesses to success. Developers can gain better insight from analyzing these data to capture the Android market!

Data source: https://www.kaggle.com/lava18/google-play-store-apps and this information is scraped from the Google Play Store.\
Data shows 10840 apps and has 13 features:  ['App', 'Category', 'Rating', 'Reviews', 'Size', 'Installs', 'Type','Price', 'Content Rating', 'Genres', 'Last Updated', 'Current Ver', 'Android Ver']

Research Hypothesis:

1. Null Hypothesis: On average does free apps on Google Play store have same rating as paid apps.\
Alternative Hypothesis: Free apps on Google Play store are different from paid apps in terms of rating.

2. In these 4 genres, Which one is different in terms of popularity? Entertainment,Education,Medical,Business.\
Null Hypothesis: all variables have the same distribution.\
Alternative Hypothesis: variables don't have the same distribution.


Hypothesis are testing using non parametric tests like Kruskal_wallis and Mood's median test.\
Data cleaning includes eliminating Nulls and converting some string data to numeric data.
