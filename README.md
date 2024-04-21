# Multi-Variant-Linear-Regression-Model-From-Scratch-Using-Synthetic-Data
This particular project was for educational purposes. 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Project Overview</h1>
    <p>This project involves the implementation of a multi-variant linear regression model from scratch using gradient descent. The goal was to predict productivity based on a dataset simulated over a 20-day routine. The dataset includes multiple independent variables such as sleep hours, food quality, working hours, health condition, and mood, with productivity as the target variable.</p>

  <h2>Data Generation</h2>
    <p>The data for this project was generated using custom functions that simulate realistic daily routines. Variables such as sleep hours and work hours were dynamically generated to ensure realistic daily totals. The quality of food, health condition, and mood were ranked and included as ordinal variables influencing the productivity outcomes.</p>

   <h2>Methodology</h2>
    <p>The linear regression model was built using numpy for numerical operations. The model utilizes gradient descent to optimize the weights and biases applied to the independent variables. This method was chosen to illustrate the underlying mechanics of linear regression models and provide hands-on experience with adjusting and tuning the model manually.</p>

   <h2>Key Features</h2>
    <ul>
        <li><strong>Data Preparation:</strong> Raw data was processed, normalized, and split into training and testing sets. This includes scaling of ordinal variables and standardization of continuous variables to improve model performance.</li>
        <li><strong>Model Building:</strong> The linear regression algorithm was implemented to adjust weights iteratively using the gradient descent optimization algorithm.</li>
        <li><strong>Analysis:</strong> The model's performance was evaluated using metrics such as Mean Squared Error (MSE) to quantify prediction accuracy on the test dataset.</li>
    </ul>

   <h2>Results and Conclusion</h2>
    <p>The implementation of the linear regression model demonstrated the capability to predict productivity based on the input variables with reasonable accuracy. Challenges such as feature scaling and model tuning were addressed, providing valuable insights into the practical aspects of machine learning model development.</p>
</body>
</html>
