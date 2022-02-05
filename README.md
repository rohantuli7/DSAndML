# Data Science and Machine Learning experimentation

This repository consists of implementation of common Data and Science and Machine Learning techniques.

## K - Means
* K - Means algorithm is an unsupervised clustering algorithm which clusters elements of similar properties (or distances like Euclidean, Manhattan etc.) according to the number of clusters mentioned by the user. This algorithm revolves around the idea of creating clusters in accordance with the number mentioned by the user and further involves multiple iterations until (i) the means of successive iterations are the same, (ii) the clusters after successive iterations remain the same or (iii) an arbitrary number of iterations mentioned by the user are made. 
* Two kinds of implementation is included in this repository: (i) consists of hard coded values enter by the user & (ii) consists of a loan amount dataset. For this experiment, the user can give any number of clusters desired and the most suitable output will be generated. At each stage, appropriate outputs have been displayed. K means is an unsupervised learning algorithm.

## Naive Bayes classifier
* The classifier is created by utilising a dataset (created within the file). The dataset mainly consisted of four important columns (namely outlook, humidity, wind and play). On the basis of these columns, we had to predict the probability of play on a day with predefined weather conditions. For day 1, there was a 100% chance of play with the given weather conditions and on day 2, there was 55% chance of play being held. 

## Linear regression
* Linear regression was implemented on a Swedish insurance dataset. Regression calculates coefficient values on a training dataset and those coefficient values can be used for predicting values in the testing dataset. 
* Initially, the dataset was split into training and testing. Each of these subdivided datasets were used for finding the regression coefficients and then predicting the values using the respective datasets. The dataset was split in a 80-20 ratio where 80% was training and 20% was testing. 
* Once the regression coefficients were found for the training set, we used those coefficients on the testing set to make a prediction. According to the above screen shots, there was a 37.2 root mean square error.
* When implementing regression, regression coefficients play a key role (in our case, b0 and b1). Here, b1 is equal to the slope and b0 is equal to the y-intercept. 
In simple linear equation, the formula y = mx + c is used extensively to predict the output. The slope indicates the steepness of a line and the intercept indicates the location where it intersects an axis. The slope and the intercept define the linear relationship between two variables, and can be used to estimate an average rate of change. The greater the magnitude of the slope, the steeper the line and the greater the rate of change.
* Thus, if the slope (m or b1) increases, there will be an increase in y and the same applies for the y – intercept (b0 or c)

## Apriori
* Apriori algorithm was implemented for finding frequent itemsets in a dataset for Boolean association rule. 
* Our own dataset was created in which, we applied pruning and join operations after which, we found itemsets which satisfied the minimum support condition (in our case 2). Once we found all the associations, we used them to generate weak and strong rules. 
* The threshold for these rules was 70% thus, there were 3 strong rules generated and 6 weak rules. 
* Thus, The Apriori algorithm is used for mining frequent itemsets and devising association rules from a transactional database. The parameters “support” and “confidence” are used. Support refers to items' frequency of occurrence; confidence is a conditional probability. Items in a transaction form an item set.

## Logic gates using Hebb network
* AND, OR, NOT, NAND & NOR gates were implemented using Hebb network. For each of the gates, their respective x1, x2 and bias values were taken. Hebbian neurons work with constant changes in weights. 
* This method of weight updation enabled neurons to learn and was named as Hebbian Learning.
Hebbian networks primarily work on the following equation:
w_new= w_new+ β.x.y (where, wnew is the new weight after the iteration, B is the bias and, x and y are input values for the respective gates.)

## Logic gates using perceptrons
* AND, OR, NOT, NAND & NOR gates were implemented using perceptrons.
* For each of the gates, their respective x1, x2 and bias values were taken. Perceptrons use activation functions for updation of values.
* The activation function used was as follows: 
<img width="157" alt="image" src="https://user-images.githubusercontent.com/49033060/152655509-244720c9-f372-4bd6-ba17-6e941e584135.png">
* The weights and biases are updated using the following equations:
<img width="221" alt="image" src="https://user-images.githubusercontent.com/49033060/152655535-e5bc4c18-d4d3-4693-97a5-1e3db3d96632.png">












