# Machine-Learning-Project

This project focused on regression analysis, data preprocessing, visualization, and classification tasks. In the regression analysis part, we utilized statistical techniques to model the relationship between a dependent variable and independent variables. The goal was to understand and predict the value of the dependent variable based on the predictors.

Data preprocessing involved loading the dataset, dropping irrelevant columns, handling missing values by filling them with the mode of corresponding features, and visualizing interest rates based on different parameters using bar plots and pie charts.

Categorical features were converted into numerical values using the "get_dummies" function from the Pandas library. A heatmap was created to explore relationships between different features.

The data was then split into training and test sets, with a ratio of 80/20. A linear regression model was trained on the training data and evaluated using Mean Squared Error (MSE) and R2 score. The model was also tested on the test data, and the corresponding MSE and R2 score were reported. Additionally, an alternative regression model was experimented with and compared against the linear regressor.

Moving on to classification, the focus shifted to building and training a model to classify composers based on notes and velocities extracted from MIDI files. The MIDI files were read from the given root directory, and a mapping from composer names to numbers was created. The notes and velocities were transformed into fixed-sized vectors for compatibility with machine learning algorithms.

Average velocity and pitch of each song were visualized using scatter plots, where composers were represented by different colors. The lengths of features and labels were checked to ensure consistency, and the data was split into train and test datasets using a test size of 0.2.

Finally, a classification model was chosen based on its suitability for the task, and the model was trained and evaluated using the f1_score metric on the test features.

Overall, this project involved a comprehensive analysis of regression, data preprocessing, visualization, and classification tasks, showcasing various techniques and models to gain insights and make predictions from the given dataset.
