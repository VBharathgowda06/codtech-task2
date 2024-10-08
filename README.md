1. Dataset Creation<br/>
Synthetic Data: We generate random data for both the independent variable (X) and dependent variable (y). The dependent variable (y) is modeled as a linear function of X with some added noise, simulating a real-world scenario where data isn't perfectly linear.<br/>
2. Data Splitting<br/>
The dataset is split into training and testing sets using train_test_split. This ensures that the model is trained on one part of the data and tested on a separate, unseen portion, which helps evaluate its performance.<br/>
3. Model Training<br/>
A Linear Regression model from the scikit-learn library is trained on the training data. The model learns the relationship between X (features) and y (target).<br/>
4. Predictions<br/>
Once trained, the model is used to make predictions on the test set.<br/>
5. Model Evaluation<br/>
The performance of the model is evaluated using:<br/>
Mean Squared Error (MSE): Measures the average squared difference between the actual and predicted values.<br/>
R-squared (R²): Indicates how well the regression model fits the data, with a value closer to 1 indicating a better fit.<br/>
6. Visualization<br/>
A scatter plot is used to visualize the actual values (blue dots) and the predicted regression line (red line), providing an intuitive understanding of how well the model fits the data.<br/>
The goal is to fit a line that best predicts the target variable (y) given the feature (X), and the visualization helps assess how well the model has performed.<br/>






