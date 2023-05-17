# Wine-quality
# Quick Insight
This dataset is red variants of spanish wines. The dataset describes several popularity and description metrics their effect on it's quality. The datasets can be used for classification or regression purposes. The classes are ordered and not balanced (quality goes from 5 to 4). The task is to predict either the quality of wine or the prices using the given data.

Content
# Source 
Data set is from Kaggle (https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset)

# Analytical Insights

![image](https://github.com/Jonher0100/Wine-quality/assets/127071673/7ef90e4e-22ea-4faa-9f38-c5d91ba49e8a)

The bar graph above shows 4.3 and 4.4 is the most common rating. 

![image](https://github.com/Jonher0100/Wine-quality/assets/127071673/00f4994f-446b-4b35-894c-647427a39754)

The chart above shows the ratings of each region. We can see that multiple regions have a 4.3 and 4.4 rating.

![image](https://github.com/Jonher0100/Wine-quality/assets/127071673/e5a5697d-eaf4-4875-88ac-102f579f2790)

Here it shows the more expensive tbe wine is the higher the rating is. This is good since wine that expensive is used for special occations. But the average consumer will probably not go over 500 for a bottle of wine.

# Best Model


Confusion Metrix
![image](https://github.com/Jonher0100/Wine-quality/assets/127071673/800d66d0-db3c-4bce-afba-0b4c355e7e0c)


Classification
Train Report
              precision    recall  f1-score   support

         4.2       0.57      0.31      0.40       165
         4.3       0.45      0.81      0.58       484
         4.4       0.40      0.31      0.35       360
         4.5       0.46      0.17      0.25       191
         4.6       0.46      0.30      0.36       132
         4.7       0.59      0.31      0.41        84
         4.8       0.71      0.32      0.44        37
         4.9       0.00      0.00      0.00         2

    accuracy                           0.46      1455
   macro avg       0.46      0.32      0.35      1455
weighted avg       0.47      0.46      0.43      1455

Test Report
              precision    recall  f1-score   support

         4.2       0.47      0.17      0.25        54
         4.3       0.39      0.78      0.52       159
         4.4       0.28      0.24      0.25       102
         4.5       0.21      0.06      0.09        86
         4.6       0.35      0.11      0.17        53
         4.7       0.67      0.42      0.51        24
         4.8       0.14      0.14      0.14         7

    accuracy                           0.37       485
   macro avg       0.36      0.27      0.28       485
weighted avg       0.35      0.37      0.31       485


This model I would use to predict the quality of spanish wine. This is a PCA LR model. This model has a 69% of having a rating of 4.2 and 4.4. The best overall percentage is 78 which has a rating of 4.3. This is the most positive outcome with the model types I tried. The price point of 4.2 and 4.3 is constistently lower than the higher priced wines. This is good so new customers can try something in this rating depending on their budget. The only recommendation would be the cost of making the product. Then, compare the cost of the other wines and determine which wine is the most popular.
