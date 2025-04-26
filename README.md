Linear Regression Project 📈
Overview
This project applies Linear Regression to predict a target variable based on customer behavior data.
The goal is to understand which features (like Time on App, Time on Website, Membership Duration) impact customer spending the most.

Problem Statement
The company wants to know whether they should focus more on improving their mobile app or website experience to boost customer purchases.

Dataset
Customer behavior data (such as Time on Website, Time on App, Length of Membership, etc.)

Target variable: Amount Spent

Workflow
📊 Exploratory Data Analysis (EDA)
Visualized feature relationships with scatter plots and pair plots.

🧹 Data Preprocessing
Handled outliers and ensured data was clean before training.

🏗️ Model Building
Built a Linear Regression model using scikit-learn.

🧮 Model Evaluation

Mean Absolute Error (MAE): 8.43

Mean Squared Error (MSE): 103.92

Root Mean Squared Error (RMSE): 10.19

📈 Insights

Time on App has a strong positive influence on Amount Spent.

Time on Website shows minimal correlation with spending.

Recommendation: The company should invest more in enhancing their app experience.

Key Libraries Used
pandas

numpy

matplotlib

seaborn

scikit-learn

Conclusion
The project clearly highlights that mobile app engagement is more important for driving customer revenue compared to the website.
Optimizing the app could significantly boost customer spending.

How to Run
Clone this repository.

Install the required libraries:

bash
pip install -r requirements.txt

Open the Jupyter Notebook:
jupyter notebook Linear_Regression_project.ipynb

Run the cells sequentially to reproduce the results.

Future Work
Try Polynomial Regression to capture non-linear relationships.

Explore Regularization Techniques like Ridge and Lasso Regression.

Use cross-validation for better model generalization.

