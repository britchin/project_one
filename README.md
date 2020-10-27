# The Google/Apple Debate

## Objective
Gaming has taken the world by storm. Whether computer, console, or app games, it seems that the world of gaming generates revenue beyond measure. We decided to use Google Play 
Store data to answer questions about how users interact with apps whether the apps are free or paid.
Further, great debates exist between Google/Android Users and Apple/iOS Users. Often, discussions of which is better than the other circulate in the tech world amongst users. 
Since this is the case, we decided to bring in a comparison dataset of gaming apps in the Apple Store! Let's explore and see how gaming apps data and user data characteristics
compare!

## Hypothesis
The overarching hypothesis is that free to play games have more installs than pay to play games (based on only Google Play Store App data)

## Goals and Questions to Answer

- Is there a correlation between game price and rating?
- Is there a correlation between installs and game price?
- Compare reviews within each category - are there any categories with higher reviews than others?
- Is there a correlation between the price of the app and the last update?
- Grouping by content rating - what are the differences in number of installs per rating group?
Join Google Play Store and Apple App Store data - compare ratings, reviews, and price. Are apps more likely to be “successful” on a Google platform vs the Apple platform? 
Or vice versa? 

# Analysis 
## Do free to play games have more installs than pay to play games? (based on Google Play Store App data only)
Here we used a sorted scatter plot to display the relationship between price and the number of installs of gaming apps in the Google Play Store
 - What we found is gaming apps in the Google Play Store that are free have significantly more installs than those that cost money. There is even a relationship between how much
 the game costs versus how many times it is installed. The higher the cost of the game, the less it is downloaded in relation to other games
![Price vs Installs](https://github.com/britchin/project_one/blob/main/Resources/Price%20vs%20Installs_Scatter.png)

## Is there a correlation game price and rating? (based on Google Play Store App data only)
Here we used a linear regression to display the relationship between the price of a game app in the Google Play Store and the rating of the game app. We were interested to know 
if Users were more likely to rate a game kindly (or harshly) if it was free or a game app they paid for.
 - What we found is that there is no real correlation between the price and the rating. It seems Users tend to be honest about their ratings whether they pay for the gaming app or
 install it for free.
 ![Price vs Installs](https://github.com/britchin/project_one/blob/main/Resources/Price%20vs%20Rating_Linregress.png)
