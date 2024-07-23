# Prediction of Bank Loan Default Using Supervised Machine Learning
To minimise or eliminate the adverse effects of loan defaults, it is critical for banks to
identify loan applicants who may have difficulties in repaying the loans and interests, and as
such determine whether the bank loans should be approved or not. For this assignment, we used an 
**Artificial Intelligence (AI)** technique called **Supervised Machine Learning (ML)** to try
to provide reasonably accurate predictions of potential loan defaulters. In order to do this, we
used a **Credit Risk dataset** obtained from the Kaggle website [here](https://www.kaggle.com/datasets/marcbuji/loan-default-prediction). We used several different
types of ML algorithms to learn from this dataset. Then we compared the results from these
different ML models and selected the best performing model, which was the Random Forest Model without Tuning. 

## Steps Taken:
1. Exploratory Data Analysis </br>
2. Dropped Unnecessary Features </br>
3. Label Encoding & Replace </br>
4. Binning </br>
5. Outlier Detection & Treatment using Log Transformation & Standard Deviation </br>
6. Impute Missing Values with Mean for Numeric Values and Mode for Categorical Values </br>
7. Changing Data Type of Column </br>
8. Normalisation </br>
9. Balancing Imbalanced Dataset by Upsampling </br>
10. Feature Importance (Includes Dropping of Columns) </br>
11. Model Training </br>
12. Model Validation and Selection of the Best Model </br>
13. Model Testing (on the Best Model) </br>

## The ML Models/Algorithms Used for this Assignment
1. XGBoost without Tuning </br>
2. XGBoost with Tuning </br>
3. ANN without Tuning </br>
4. ANN with Customised Hyperparameters </br>
5. Adaboost without Tuning </br>
6. Adaboost with Tuning </br>
7. LDA without Tuning </br>
8. LDA with Tuning </br>
9. Random Forest without Tuning (the Best One) </br>
10. Random Forest with Tuning </br>
11. SVM without Tuning </br>

## How to run the program
1. Ensure that you have Anaconda and Jupyter Notebook installed on your device
2. Unzip the zipped file and ensure that the dataset ‘Data_Train’ is in the same folder location as the .ipynb file.
3. The .ipynb file makes use of several packages, such as xgboost and plotly, so please ensure that you have installed all the packages used in the file.
4. Execute all the commands in the file. After executing the last code segment, you should see a Tkinter window at the bottom of the screen.
5. Click on the Tkinter window and test out the Loan Default Predictor Program.

Hope you enjoy testing out our code!! 😀


