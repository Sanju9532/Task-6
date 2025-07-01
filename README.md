I imported the dataset and checked for null values and data types. There were no null values, and all columns were in the appropriate data types. Next, 
I separated the input and output variables and performed a train-test split. I built a KNeighborsClassifier model, achieving excellent accuracy and confusion matrix scores. 
I then experimented with various values of K, finding that all values resulted in a perfect accuracy score of 1 for both training and testing. After that, 
I selected only two input features and built another KNeighborsClassifier model, which also yielded the same impressive accuracy. Finally, I visualized the decision boundaries 
to better understand the model's performance
