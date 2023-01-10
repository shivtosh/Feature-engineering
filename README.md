# Feature-engineering
> DATA DESCRIPTION:   sensor-data.csv : (1567, 592). 
> * The data consists of 1567 examples each with 591 features.
> * The dataset presented in this case represents a selection of such features where each example represents a single production entity with associated measured features and the labels represent a simple pass/fail yield for in house line testing. 
> * Target column “ –1” corresponds to a pass and “1” corresponds to a fail and the data time stamp is for that specific test point.

Steps and tasks: 
1. Import and explore the data.
2. Data cleansing:
> • Missing value treatment.
> • Drop attribute/s if required using relevant functional knowledge.
> • Make all relevant modifications on the data using both functional/logical reasoning/assumptions.
3. Data analysis & visualisation:
> • Perform detailed relevant statistical analysis on the data.
> • Perform a detailed univariate, bivariate and multivariate analysis with appropriate detailed comments after each analysis.
4. Data pre-processing:
> • Segregate predictors vs target attributes
> • Check for target balancing and fix it if found imbalanced.
> • Perform train-test split and standardise the data or vice versa if required.
> • Check if the train and test data have similar statistical characteristics when compared with original data.
5. Model training, testing and tuning: • Model training:
> - Pick up a supervised learning model.
> - Train the model.
> - Use cross validation techniques.

> - Apply hyper-parameter tuning techniques to get the best accuracy.
Suggestion: Use all possible hyper parameter combinations to extract the best accuracies.
> - Use any other technique/method which can enhance the model performance.

> - Display and explain the classification report in detail.
> - Design a method of your own to check if the achieved train and test accuracies might change if a different sample population can lead to
new train and test accuracies.

> - Apply the above steps for all possible models that you have learnt so far.
> • Display and compare all the models designed with their train and test accuracies.
> • Select the final best trained model along with your detailed comments for selecting this model.
> • Pickle the selected model for future use.
> • Import the future data file. Use the same to perform the prediction using the best chosen model from above. Display the prediction results.
6. Conclusion and improvisation:
> • Write your conclusion on the results.
