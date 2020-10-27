# The Google/Apple Debate - Gaming

![Gaming Image](https://cdn.mos.cms.futurecdn.net/skhxF9RhghquJuv7GfnCWR-1024-80.jpg.webp)

## Objective
Gaming has taken the world by storm. Whether computer, console, or app games, it seems that the world of gaming generates revenue beyond measure. We decided to use Google Play 
Store data to answer questions about how users interact with apps whether the apps are free or paid.
Further, great debates exist between Google/Android Users and Apple/iOS Users. Often, discussions of which is better than the other circulate in the tech world amongst users. 
Since this is the case, we decided to bring in a comparison dataset of gaming apps in the Apple Store! Let's explore and see how gaming app data and user data characteristics
compare!

## Hypothesis
The overarching hypothesis is that free to play games have more installs than pay to play games (based on only Google Play Store App data)

## Goals and Questions to Answer

- Is there a correlation between installs and game price?
- Is there a correlation between game price and rating?
- Compare reviews within each subcategory - are there any subcategories with higher reviews than others?
- Is there a specific content rating where apps have more installs?


# Analysis 
## Do free to play games have more installs than pay to play games? (based on Google Play Store App data only)
Here we used a sorted scatter plot to display the relationship between price and the number of installs of gaming apps in the Google Play Store
 - What we found is gaming apps in the Google Play Store that are free have significantly more installs than those that cost money. There is even a relationship between how much
 the game costs versus how many times it is installed. The higher the cost of the game, the less it is downloaded in relation to other games
![Price vs Installs](https://github.com/britchin/project_one/blob/main/Resources/Price%20vs%20Installs_Scatter.png)

## Is there a correlation game price and rating? (based on Google Play Store App data only)
Here we used a linear regression to display the relationship between the price of a game app in the Google Play Store and the rating of the game app. We were interested to know 
if Users were more likely to rate a game kindly (or harshly) if it was free or a game app they paid for.
 - What we found is that there is no real correlation between the price and the rating. It seems Users tend to be honest about their ratings whether they pay for the gaming app or install it for free.
 
 ![Price vs Rating](https://github.com/britchin/project_one/blob/main/Resources/Price%20vs%20Rating_Linregress.png)
 
 ## Analyzing reviews per subcategory, which subcategories have a higher review count than others? (based on Google Play Store App data only)
 Here we used a bar chart to better visualize the average number of reviews exisitng within each subcategory. We were interested to know which gaming apps are most popular according to number of reviews.
 - What we found is that two subcategories (Action and Arcade) are much more likely to be reviewed that others, possibly indicating higher popularity in these subcategories.
 
 ![Average Reviews per SubCategory](https://github.com/britchin/project_one/blob/main/Resources/Average%20Number%20of%20Reviews%20by%20Sub%20Category.png)
 
 ## How many installs exist per content rating category? Is there a content rating category that is favored more amongst Users? (based on Google Play Store App data only)
 Here we used a bar chart to analyze the average number of installs per content rating category
 - We found that Everyone 10+ and Mature 17+ were the most installed content rating categories. We assumed that the Everyone content category would have had the most installs since these games would encompass more of the population, however that was not the case here. 
 
  ![Average Installs by Rating](https://github.com/britchin/project_one/blob/main/Resources/Average%20Installs%20by%20Rating.png)
  
# Google Play Store Observations
Free to play games seem to be the way to go if anyone is considering building a gaming app. There is an obvious difference in the amount of installs on free to play games versus paid gaming apps. We've assumed that the source of revenue in free to play games comes from in-app purchases and add-ons. Further, the gaming apps with the most installs come from the Action and Arcade subcategories and where the content rating is either age 10+ or age 17+.
  
# Google vs. Apple

![Google vs. Apple](https://www.techaheadcorp.com/wp-content/uploads/2019/01/android-vs-ios-which-platform-better-for-app-development.png)

## Goals and Questions to Answer

Join Google Play Store and Apple App Store data - compare ratings, reviews, and price. Are apps more likely to be “successful” on a Google platform vs the Apple platform? 
Or vice versa?

## Is a gaming app likely to be more expensive in the Google Play Store or the Apple App Store?
Here we used a bar chart to compare the total cost of the same exact games in both the Google Play Store and the Apple App Store. There were a total of 600 entries that matched in both datasets after being merged. 
 - We found that the total price of all 600 gaming apps is more higher in the Apple App Store than they are in the Google Play Store
 
![Google vs. Apple Total Price](https://github.com/britchin/project_one/blob/main/Resources/Apple%20vs%20Google%20Total%20Price.png) 

## Further, what is the average difference in price when comparing the same game app's price in the Google Play Store versus the Apple App Store?
Here we used a bar chart to compare the difference in price of the same exact games in both the Google Play Store and the Apple App Store. We then found the average of this difference in price.
 - We found that on average, a User will pay $0.47 more for a gaming app in the Apple App Store versus the Google Play Store. Interestingly though, more of the paid gaming apps showed a difference in price of up to $6.00 in some cases!
 
![Average Difference in Cost](https://github.com/britchin/project_one/blob/main/Resources/Average%20Difference%20in%20Cost.png)

## Is a gaming app more likely to be reviewed in the Google Play Store or Apple App Store?
Here we used a bar chart to compare the average number of reviews of the same exact games in both the Google Play Store and the Apple App Store. 
 - We found a stark difference in the average number of reviews in the Google Play Store versus the Apple App Store. On average, a gaming app in the Google Play Store will have 275,554 more reviews than a gaming app in the Apple App Store!
 
 ![Average Reviews](https://github.com/britchin/project_one/blob/main/Resources/Average%20Number%20of%20Reviews.png)
 
 ## Further, based on the number of reviews for gaming apps on each platform, are there any differences in the ratings of these apps?
 Here we used a bar chart to compare the average rating of the same exact games in both the Google Play Store and the Apple App Store. 
  - Shockingly enough, we found an insignificant difference in how User's rate the same gaming apps across the two platforms! Although there was no correlation between the price and rating of the app in the Google Play Store, does this mean that User's using the Apple App Store are more likely to rate a game higher than User's in the Google Play Store?
  
![Average Gaming App Rating](https://github.com/britchin/project_one/blob/main/Resources/Average%20Rating.png)

# Observations
Gaming apps are not more likely to be "successful" on a Google platform or on Apple's platform or vice versa. According to the average rating, gaming apps as a whole a rated quite similarly. Gaming apps are more likely to be reviewed in the Google Play Store vs the Apple App Store. And sadly in some cases of pay to play gaming apps, Users are going to be more likely to pay more for a gaming app in the Apple App Store than they would in the Google Play Store.



- Sources 
  -- Images:https://cdn.mos.cms.futurecdn.net/skhxF9RhghquJuv7GfnCWR-1024-80.jpg.webp, https://www.techaheadcorp.com/wp-content/uploads/2019/01/android-vs-ios-which-platform-better-for-app-development.png
  -- Data: https://www.kaggle.com/gauthamp10/google-playstore-apps,https://www.kaggle.com/tristan581/17k-apple-app-store-strategy-games 
