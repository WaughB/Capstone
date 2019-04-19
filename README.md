# Predicting Starbucks Locations
> Author Note: Brett Waugh, School of Information, University of South Florida

The code for this project can be found [here](capstone.R). The markdown can be found [here](capstone.Rmd), along with the output of the markdown [here](Capstone_Markdown.docx).
The white paper for the project can be found [here](Waugh-Capstone.pdf). 
The original dataset is [here](directory.csv) along with the additional dataset [here](addData.csv).

## Introduction
Predicting the number of Starbucks locations has many practical uses and interested groups. Starbucks is interested in predicting where they should put a new franchise and competing companies may want this information in order to prepare for the new competition. This study walks through six different methods for predicting Starbucks locations. The first three methods use data Starbucks provided and show methods that everyday individuals may use to predict Starbucks locations. The next three methods will use data from several sources and more advanced modeling techniques to predict Starbucks locations. The benefits and costs of each method are discussed; exploring if using more complex modeling is warranted over other methods.

## Methods Used
### Methods one, two, and three are conventionally used methods. 
* Mean
![Number of Starbucks by State](/images/Number_of_Starbucks_by_State.jpeg)
* Within a Standard Deviation, Removing Outliers
![Starbucks by State, without outliers](/images/no_outlier_number_starbucks_by_state.jpeg)
* Linear Regression
![Lattitude and Longitude Linear Regression](/images/m4_linear_regression.jpeg)

### Methods four, five, and six are more advanced methods. 
* Multivariate Linear Regression
* Logistic Regression
* Support Vector Machine (SVM)
![Results of the Models](/images/model_results.jpeg)

## Conclusion
There are numerous methods to help people predict the number of Starbucks in an area. The first three methods focused on more traditional methods that people who are not familiar with more advanced techniques would use. These techniques gave people a sense of familiarity with the data but did not provide much depth to the technique. The first three methods also had a very wide range, with little distinction between states. The last three methods built off other features to give more context into the areas that Starbucks tend to appear in. Using these types of techniques, Starbucks location prediction is much more accurate. 
If more granular data was available regarding population, median income, crime rates, and number of Universities by city instead of solely by state then the models may have performed better. The original intent was for the models to perform at the city-level, but a lack of data for all cities forced the models to perform at the state level. 



## References
Dietrich, D., Heller, B., & Yang, B. (2015). Data Science & Big Data Analytics: Discovering, Analyzing, Visualizing and Presenting Data. Indianapolis, IN: Wiley.

Downey, A. B. (2015). Think Stats [2.0.38]. Retrieved January 20, 2019.

Enchanted Learning, & U.S. Census Bureau. (2017, July 1). US States: Population and Ranking. Retrieved April 13, 2019, from https://www.enchantedlearning.com/usa/states/population.shtml

James, G., Witten, D., Hastie, T., & Tibshirani, R. (2017). An introduction to Statistical Learning: With Applications in R. Retrieved January 20, 2019.

Johnson, M., Jr. (2016, December 28). United States crime rates by county. Retrieved April 13, 2019, from https://www.kaggle.com/mikejohnsonjr/united-states-crime-rates-by-county

Matloff, N. (2013). The Art of R programming: A tour of statistical software design. San Francisco, CA: No Starch Press.

National Center for Education Statistics, & U.S. Department of Education. (2013, August 12). Colleges and Universities in the United States of America (USA) by State/ Possession. Retrieved April 13, 2019, from http://www.univsearch.com/state.php

Rich, K. T. (2017). Machine learning intro in R: Support Vector Regression. Retrieved April 16, 2019, from https://rpubs.com/richkt/280840

Starbucks. (2017, February 13). Starbucks Locations Worldwide. Retrieved February, 2019, from https://www.kaggle.com/starbucks/store-locations

U.S. Census Bureau, & Wikipedia. (2018, December 28). List of U.S. states and territories by income. Retrieved April 13, 2019, from https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_income

Welling, M. (2010). A First Encounter with Machine Learning. Retrieved January 20, 2019.

Zaki, M. J., & Meira, W. (2014). Data mining and analysis: Fundamental concepts and algorithms. Retrieved January 20, 2019.

Zhao, Y. (2013). R and Data Mining: Examples and Case Studies. Retrieved January 20, 2019, from http://www.RDataMining.com 

## License
This project is [MIT licensed](LICENSE).
