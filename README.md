# Data-Science-Group-Project
###### Group project for CST383:Introduction to Data Science.  Contains published code, a readme.md that acts as a report, and a link to a presentation video.

## Presentation Video Link
[![Watch the video](https://img.youtube.com/vi/TZSPXR9PsAI/maxresdefault.jpg)](https://youtu.be/TZSPXR9PsAI)

## Introduction
###### Our chosen data set Google Play Store Apps from Lavanya on Kaggle. We are interested most in seeing if an app’s number of downloads, reviews, and rating correlate with whether it is a free or paid app. The results would be useful for consumers to know when considering an app purchase

## Selection of Data
###### Our dataset was scraped (with no munging) right from the Google Play Store, and includes over 9,500 different apps. For each app, it included key statistics such as category, user rating, number of installs, and price (if it is not free). Because of the range of statistics, it gave our team a broad spectrum of questions we could posit with the data.

## Methods
###### To analyze this dataset, we relied on a number of tools:
* Python Libraries:
  * Numpy
  * Pandas
  * Matplotlib
  * Seaborn
  * Sklearn
* Tools:
  * JupyterLab

## Reults
###### Here is the number of free app downloads compared to paid app downloads
![picture alt](https://user-images.githubusercontent.com/74388707/155828645-7bd6c38f-d0ea-4142-9506-5aca9637cb0a.png)

###### Our confusion matrix shows that while we were able to predict on statistics whether an app was free, we had more issues properly identifying paid apps accurately 
![image](https://user-images.githubusercontent.com/74388707/155828686-e4b09393-1528-4151-bbb5-092f20d6ff70.png)

##### Our confusion matrix can be explained by viewing this visualization of app sizes by counts. Note the paid in orange is significantly less, indicating a smaller sample size for us to work with
![image](https://user-images.githubusercontent.com/74388707/155828722-76df928d-aebc-497e-908d-365219ee54b5.png)

##### Despite this, we were able to still notice that paid apps on average had a slightly higher rating than free apps on average.
![image](https://user-images.githubusercontent.com/74388707/155828738-5c525b2b-87ae-474e-b875-28bfcc9ffa13.png)

##### Finally, the last major trend we noticed was when we graphed the reviews log with the log of minimum downloads, showing that along with being rated higher on average, paid apps were also more likely to be given a review than a free app.
![image](https://user-images.githubusercontent.com/74388707/155828747-2dfa5602-7fb2-46a8-bbd4-087f12111996.png)


## Discussion
###### In conclusion, we believe our results imply that paid apps are more likely to be rated and reviewed compared to free ones, even though they are downloaded less. This matters for consumers who are considering making an app purchase when a comparable competitor is available for free. This supports research from Aapo Markkanen, a data analyst for consumer mobility at ABI Research. He found that there are a growing number of free apps being released compared to a diminishing amount of paid apps, even though the top apps  on the market had higher rates of being paid. The perspective for future research is that ratings and reviews should be taken into account when analyzing a consumer’s interaction with a paid app vs a free one!

## Summary
###### From our data, we can see consistent trends. In spite of a smaller sample size, paid apps were more likey to be reviewd and more likely to be rated higher. However, they were also less likely to be installed and less likely to be predicted accurately as a paid app by our algorithms.

