
🤖 Excited to share my recent Machine Learning project where I tackled a fascinating challenge using supervised learning! 🚀 The objective was to predict employee salaries based on various features within the HR dataset.

Throughout this project, I performed a series of detailed steps to ensure thorough data analysis and model accuracy:

*1️⃣ Importing Libraries and Loading Dataset:* Started by importing necessary libraries and loading the HR dataset.

*2️⃣ Data Copy:* Created a copy of the raw data for future reference and comparison.

*3️⃣ Data Understanding and Cleaning:*
   - *a)* Utilized methods like head, tail, info, shape, size, and describe to understand the dataset's structure and check for null values.
   - *b)* Identified missing values and replaced them with NaN for clarity in data representation.
   - *c)* Adjusted the data type of the Total_Sales column for consistency in calculations.
   - *d)* Calculated the percentage of missing values and strategized using KNN Imputer to fill NaN values effectively.

*4️⃣ Exploratory Data Analysis (EDA):*
   - *a)* Conducted a comprehensive count of all variables to assess data completeness.
   - *b)* Investigated skewness and visualized distributions using histogram plots to understand data spread.
   - *c)* Analyzed variable distributions to identify patterns and potential insights.

*5️⃣ Statistical Approach Using Pingouin:*
   - *a)* Utilized the Pingouin library to validate observations from EDA, focusing on QQ plots to confirm distribution assumptions.
   - *b)* Identified unequal distributions and outliers, providing statistical justification.

*6️⃣ Correlation Analysis:* 
   - Employed heatmap visualization with Spearman correlation to explore relationships between variables.

*7️⃣ Relationship Exploration:* 
   - Investigated correlations between categorical independent variables and the dependent variable (Salary) using appropriate statistical methods.

*8️⃣ Scatter Plot Analysis:* 
   - Used scatter plots to visualize relationships among numeric variables, aiding in understanding potential predictors of salary.

*9️⃣ Outlier Detection:* 
   - Applied box plots to detect outliers across independent variables, crucial for data integrity and model accuracy.

*1️⃣0️⃣ Preprocessing and Feature Engineering:*
   - *a)* Implemented strategies for handling outliers and ensuring data robustness.

*1️⃣1️⃣ Sanity Check:* 
   - Verified the successful removal of outliers to maintain model integrity and performance.

*1️⃣2️⃣ Model Building:* 
   - *a)* Defined salary as the dependent variable and all other variables as independent.
   - *b)* Split the dataset into dependent and independent variables, further dividing them into actual and predicted values.
   - *c)* Applied data normalization techniques using sklearn to optimize model performance.
   - *d)* Evaluated and selected the most accurate model for predicting salary.
   - *e)* Conducted cross-validation for each model to ensure robustness.

*1️⃣3️⃣ Project Deployment:*
   - *a)* Utilized the pickle and tkinter libraries to save the model and create a user-friendly interface. This interface allows users to input data and predict salaries with the click of a button.

Stay tuned for deeper insights into each phase of this exciting journey!

#MachineLearning #DataScience #HRAnalytics #PredictiveAnalytics #ContinuousLearning
