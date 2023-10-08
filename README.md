# Applied-Machine-Learning
Worked on predicting the price by analyzing different features such as wheels, engine, Mileage, etc. The following tasks were performed on the data set:
1. EDA on the data set: Summarize the data; Display the statistical values for each of the attributes, along with visualizations (e.g., histogram) of the distributions for each attribute.
2. Explained noticeable traits for key attributes. Are there any attributes that might require special treatment? If so, what special treatment might they require?
3. Analyze and discuss the relationships between the data attributes, and between the data attributes and label. This involves computing the Pearson Correlation Coefficient (PCC) and generating scatter plots.
4. Selected 20% of the data for testing. Verified whether the test portion of the data is representative of the entire dataset.
5. Trained a Multi - Multi-linear regression model using the training data with four-fold cross-validation using MSE. Conducted the same with a closed-form solution (using the Normal Equation or SVD) and with SGD.
6. Performed Ridge, Lasso, and Elastic Net regularization – experimented with a few values of penalty term and described its impact.
7. Explored the impact of other hyperparameters, like batch size and learning rate (no need for grid search). Describe your findings. For SGD, visualized the training and validation loss as a function of training iteration.
8. Further checked the performance of the model with polynomial regression. Using validation loss, explored if the model overfits/underfits the data.
9. Made predictions of the labels on the test data, using the trained model with chosen hyperparameters.
10. Summarized performance using the appropriate evaluation metric. 
