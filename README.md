# Spanish-Red-Wine-Analysis
## Classification Analysis on predicting Spanish Red Wine Ratings by analyzing over +2000 Red Wine data.

**Author**: Martisha Owens

### Business problem:

Help predict the ratings of various red wines based on year, region, country, price, type of wine variety, body, and acidity.


### Data:
Spanish Wine Quality Dataset. fedesoriano. (April 2022). 
https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset


## Methods
- Developed multiple models, hypertuned models, and combined models to predict the ratings:
  - Dropped Country due to the model focusing stricting on Spain, number of reviews since it is not a defining feature of the actual wine itself, and winery to prevent overfitting.
  - Used the median Simple Imputer to fill in the missing data for Year, Body, and Acidity. We also used the most frequent Simple Imputer for wine type.
- Based on the heatmap below, ratings had the highest correlation with price at a moderate correlation coefficient of +0.51. It then had some positive correlation with body at +0.21 and negative correlation with year at -0.26.

![sample image](https://github.com/Martishamao/Spanish-Red-Wine-Analysis/blob/main/Wine%20Heatmap.png)

## Results
- The Boxplot below indicates that ratings data did not have much of an outlier, with just one noticed outlier at 4.9. 
- Price on the other hand had quite a few outliers on the higher end. The 75th percentile was 110 but there were outliers that ranged all the way up to 3,119.
![sample image](https://github.com/Martishamao/Spanish-Red-Wine-Analysis/blob/main/Wine%20Box%20Plots.png)

- With the correlation between Rating and Price in mind, I have created the Multivariate exploratory visuals below to explore further with the ratings limited between 4.0 and 5.0.
- In terms of Wine types, Pedro Ximenez had an average rating above all other wine types. Coming in behind was Toto Red, Tempranillo, and Ribera Del Duero Red.

![sample image](https://github.com/Martishamao/Spanish-Red-Wine-Analysis/blob/main/Price%20v.%20Rating.png)

## Recommendations:

- In Conclusion, I would not recommend my model to predict the rating of the Spanish Red wine. I believe a better hypertuning strategy could be conducted to increase the accuracy of the test data to match the training data.

![sample_image](https://github.com/Martishamao/Spanish-Red-Wine-Analysis/blob/main/Wine%20Confusion%20Matrix.png)
### For further information


For any additional questions, please contact MartishaOwens@gmail.com
