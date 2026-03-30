# **PROJECT REPORT - WEATHER PREDICTION USING NAIVE BAYES**





\#Bayes' theorem can be written as:

\-Probability of hypothesis H given evidence E = (Probability of evidence E given hypothesis H × Probability of hypothesis H) divided by Probability of evidence E

&#x20;Or in formula form:

\-P(H|E) = (P(E|H) × P(H)) / P(E)Probability-Based Weather Predictor Using Bayesian Classifier





### 1\. Introduction:



\->Predicting weather is one of the oldest scientific challenges. In this project, I tried to build a simple probability-based model that  predicts whether it will rain or not using historical weather data. Instead of complex simulations, I used a fundamental AI/ML technique: Bayesian classification.





### 2\. Why This Problem Matters:



\-Farmers depend on rainfall prediction for crop planning.

\-Cities need forecasts to prepare for floods or droughts.

\-People use weather predictions for daily decisions like they should travel outside or participate in outdoor activities.

\--For me as a student, this project helped me understand how probability and machine learning can be applied to real-world problems.





### 3\. Approach:



\->I used the Naive Bayes Classifier, which is based on Bayes’ theorem. The formula is:



\[ P(H|E) = (P(E|H) × P(H)) / P(E) ]



Where:

(H) = Hypothesis (Rain or No Rain)

(E) = Evidence (features like humidity, temperature, wind speed)



#### 

##### \*\*Steps I Followed (Simplified):



1.Gather Data: Collected past weather information like temperature and humidity.

2.Clean Data: Fixed missing or wrong data and grouped numbers into simple categories like low or high.

3.Pick Important Features: Chose the most useful weather details, like humidity and pressure.

4.Train Model: Used a simple method (Naive Bayes) to learn from the data.

5.Make Predictions: Used the model to guess if it will rain or not based on new weather data.



#### 

#### 4\. Key Decisions:



\-I chose Naive Bayes because it is simple, fast, and easy to understand.

\-I converted continuous data into categories to simplify probability calculations.

\-I used accuracy and confusion matrix to evaluate the model.



#### 

#### 5\. Challenges Faced:



\-Data Quality: Some records had missing or inconsistent values.

\-Independence Assumption: Naive Bayes assumes features are independent, but in weather data, they are often correlated.

\-Class Imbalance: Rainy days were fewer compared to non-rainy days, which affected prediction balance.





#### 6\. Results:



\-The model achieved around 75–80% accuracy depending on the dataset.

\-Humidity and pressure were the strongest indicators of rainfall

\-Even though the model was simple, it gave interpretable and useful results.





#### 7\. Learnings:



\-Probability is a strong foundation in AI/ML.

\-Simple models can still be effective if applied correctly.

\-Understanding the assumptions of a model is important before applying it.





#### 8\. Conclusion:



\->This project showed me how probability-based classifiers can be applied to weather prediction. While it is not as advanced as modern forecasting systems, it is a great way to learn the fundamentals of AI/ML. The project helped me connect theory with practice and gave me confidence in applying machine learning concepts to real-world problems.

