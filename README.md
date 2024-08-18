# Purpose of the dataset
The primary objective of this analysis is to develop a predictive model to estimate the silica content in iron ore concentrate, which represents the level of impurity within the ore. The ability to predict the percentage of silica is crucial, as it currently requires an hour to be accurately measured in laboratory settings. By providing predictive insights into the silica content, engineers can receive timely information, enabling them to implement corrective actions and optimize the production process. This proactive approach not only aims to minimize impurities but also contributes to environmental sustainability by reducing the amount of ore directed to tailings through more efficient processing.

# Machine learning models
We began the process by dividing the dataset into training and testing sets. Following this, we employed decision tree and random forest regression models to predict the percentage of silica in the ore concentrate.

# Conclusion
After testing various algorithms, we recorded their performance metrics, including RMSE and R² scores. Our analysis indicated that the Random Forest Regressor performed more effectively on the larger dataset. Specifically, it predicted the percentage of silica concentrate with a Mean Squared Error of 0.0618 and an R-squared value of 0.951 on the large original dataset. Finally we deployed the project over Gardio.

# All files:

[Power BI + Presentation + colab notebook](https://drive.google.com/drive/folders/16AgHm4TuZJFEtl20IzWk9KHCAUqaZfga)

NOTE: you can run the note book to see the deployment.
