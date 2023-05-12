# Wine-quality
# Quick Insight
Finding the quality of spanish wine. This is important so the company can see what the average consumer would enjoy. The end goal is to get more returning customers.
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

Classification

Train Report
              precision    recall  f1-score   support

         4.2       0.87      0.75      0.80       165
         4.3       0.74      0.88      0.81       484
         4.4       0.75      0.78      0.76       360
         4.5       0.76      0.60      0.67       191
         4.6       0.66      0.59      0.62       132
         4.7       0.71      0.60      0.65        84
         4.8       0.79      0.59      0.68        37
         4.9       0.00      0.00      0.00         2

    accuracy                           0.75      1455
  

Test Report
              precision    recall  f1-score   support

         4.2       0.61      0.35      0.45        54
         4.3       0.42      0.58      0.49       159
         4.4       0.23      0.29      0.26       102
         4.5       0.33      0.17      0.23        86
         4.6       0.35      0.17      0.23        53
         4.7       0.44      0.50      0.47        24
         4.8       0.20      0.14      0.17         7

    accuracy                           0.37       485



Confusion Metrix

![image](https://github.com/Jonher0100/Wine-quality/assets/127071673/1370075f-329b-461e-afe8-7f667715231d)

Tnis model I would use to predict the quality of spanish wine. This is a regular random forest model. This model has a 70% of having a rating of 4.2 and a 67% of being a 4.3. This is the most positive outcome with the model types I tried. The price point of 4.2 is constistently lower than the higher priced wines. This is good so new customers can try something in this rating depending on their budget. The only recommendation would be the cost of making the product. Then, compare the cost of the other wines and determine which wine is the most popular.
