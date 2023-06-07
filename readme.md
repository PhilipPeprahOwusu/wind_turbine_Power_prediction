<h1>Analysis and Prediction of Turbine Project Capacity</h1>
Documentation prepared by <a href="https://github.com/PhilipPeprahOwusu">Philip Peprah Owusu</a><br>

<h2>Project Summary</h2>
This project was conducted as part of a school project and aimed to analyze and predict the total project capacity of turbines based on various features. The data was prepared by cleaning and selecting relevant columns, followed by exploratory data analysis to visualize the relationships between the variables. Linear regression modeling was performed, and statistical analysis was conducted to assess multicollinearity and heteroscedasticity. Feature selection techniques were applied, and classification models (K-Nearest Neighbors and Support Vector Classifier) were implemented and evaluated. The project involved data preparation, exploratory analysis, regression modeling, statistical analysis, feature selection, and classification modeling, with the goal of understanding the relationships between turbine features and project capacity and making accurate predictions.

 <h2>Data Preparation</h2>
    <p>Began by importing the necessary libraries and loading the data from the 'Turbine.csv' file. I selected the relevant columns and renamed them for convenience. To ensure data quality, I performed data cleaning by converting the 'turbineCapacity' column to numeric type and dropped rows with missing values.</p>

<h2>Exploratory Data Analysis</h2>
    <p>Visualized the pairwise relationships between the selected variables using a pairplot from the seaborn library. Additionally, I plotted a heatmap to visualize the correlation matrix between the variables.</p>

<h2>Model Development and Evaluation</h2>
    <p>Prepared the input features (turbineCapacity, rotorDiameter, hubHeight) and the target variable (projectCapacity). To standardize the input features, I used the StandardScaler from scikit-learn. Next, I split the data into training and testing sets for model evaluation. I performed linear regression using the LinearRegression model from scikit-learn. I calculated and printed the mean of residuals, testing accuracy, coefficient, intercept, and root mean squared error (RMSE). Additionally, I fitted the linear regression model using the statsmodels library to conduct further statistical analysis.</p>

<h2>Statistical Analysis</h2>
    <p>To assess multicollinearity, I calculated the condition number of the model matrix. I also conducted the Breusch-Pagan test to check for heteroscedasticity.</p>

<h2>Feature Selection</h2>
    <p>To identify features with high multicollinearity, I plotted the correlation matrix using a heatmap. Additionally, I calculated the Variance Inflation Factor (VIF).</p>

<h2>Classification</h2>
    <p>Implemented and evaluated two classification models: K-Nearest Neighbors (KNN) and Support Vector Classifier (SVC). I printed classification reports to assess the performance of the models.</p>

<p>Overall, this project involved data preparation, exploratory data analysis, linear regression modeling, statistical analysis, feature selection, and classification modeling. My purpose was to gain insights into the relationships between turbine features and project capacity, predict project capacity using regression models, and evaluate the performance of classification models. My motivation for this project was to contribute to the understanding of turbine capacity and provide useful tools for the renewable energy industry in planning and optimizing future wind energy projects.</p>

