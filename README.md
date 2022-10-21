# Spanish-Red-Wine-Analysis
##Classification Analysis on predicting Spanish Red Wine Ratings by analyzing over +2000 red wines.

**Author**: Martisha Owens

### Business problem:

Help predict the proper ratings of various red wines based on year, country, region, price, type of wine variety, body, and acidity..


### Data:
Spanish Wine Quality Dataset from https://www.kaggle.com/datasets/fedesoriano/spanish-wine-quality-dataset.


## Methods
- Developed multiple models, hypertuned models, and combined models to predict the ratings:
  - Dropped Country due to the model focusing stricting on Spain, number of reviews since it is not a defining feature of the actual wine itself, and winery to prevent overfitting.
  - Used the median Simple Imputer to fill in the missing data for Year, Body, and Acidity. We also used the most frequent Simple Imputer for wine type.


## Recommendations:

> In Conclusion, I would not recommend my model to predict the rating of the Spanish Red wine. I believe a better hypertuning strategy could be conducted to increase the accuracy of the test data to match the training data.


### For further information


For any additional questions, please contact MartishaOwens@gmail.com
