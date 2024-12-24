# Employee Burnout Analysis
### Introduction
This project aims to predict and analyze employee burnout using machine learning techniques. Burnout is a common issue in organizations that impacts employee well-being and productivity. By leveraging data-driven methods, this project identifies key factors contributing to burnout and provides actionable insights to mitigate risks.
### Problem Statement
Employee burnout is a significant challenge faced by organizations worldwide. It adversely affects productivity, morale, and overall company performance. This project focuses on building a predictive model to analyze burnout based on workplace data, enabling organizations to implement timely interventions.
### System Development Approach
#### System Requirements
##### Hardware:
A basic system with moderate memory (4GB RAM or more) and CPU capability.    
##### Software:
Google Colab (for seamless execution of Python code).     
Python 3.x environment.     
##### Libraries Used
##### Ensure you have the necessary Python packages installed.If it's not present, you may need to install following packages.
Pandas: For data manipulation and preprocessing.    
NumPy: For mathematical computations.    
Matplotlib & Seaborn: For data visualization.    
Scikit-learn: For data scaling, model training, and evaluation.     
### Dataset
The dataset used in this project includes anonymized employee details, such as mental fatigue scores, resource allocation, company type, and more. It also contains the target variable, Burn Rate, which indicates the level of burnout experienced by employees.
#####  Dataset Details
File Format: Excel    
Source: [employee_burnout_analysis-AI 2.xlsx](https://github.com/user-attachments/files/18241523/employee_burnout_analysis-AI.2.xlsx)
### Project Workflow
##### Data Preprocessing:
Handle missing values.   
Drop irrelevant columns (e.g., Employee ID).   
Feature engineering using one-hot encoding for categorical variables.   
##### Exploratory Data Analysis (EDA):
Visualize categorical and numerical data relationships.    
Correlation analysis to identify important features.    
##### Model Development:
Linear Regression was used as the predictive model.    
Data scaling using StandardScaler.    
##### Model Evaluation:
Metrics used: Mean Squared Error (MSE), Root Mean Squared Error (RMSE), Mean Absolute Error (MAE), and R-squared (R²).
##### Deployment (Google Colab):
The entire project was executed on Google Colab for ease of use and accessibility.
### Results
The Linear Regression model successfully predicted burnout risks with the following evaluation metrics:    
Mean Squared Error (MSE): 0.0031569779113610717    
Root Mean Squared Error (RMSE): 0.0561869905882231    
Mean Absolute Error (MAE): 0.04595032032644773    
R-squared (R²): 0.918822674247248    
### Conclusion
This project demonstrated the effectiveness of using data-driven techniques to predict employee burnout. The model highlights key features influencing burnout, enabling organizations to take proactive measures. Challenges such as missing data were addressed during preprocessing, and the model provides reliable predictions based on the available data.
### Future Scope
##### Model Improvements:
Experiment with more complex models like Random Forest or XGBoost.
##### Real-Time Predictions:
Deploy the model into a web or mobile application for live predictions.
##### Incorporating More Features:
Include additional factors like employee satisfaction, work culture, and team dynamics for a more comprehensive analysis.
### How to Run
##### Clone this repository:
git clone https://github.com/Bhoomikak18/employee_burnout_analysis.git  
Open the EBA_Project.ipynb notebook in Google Colab.    
Upload [employee_burnout_analysis-AI 2.xlsx](https://github.com/user-attachments/files/18241461/employee_burnout_analysis-AI.2.xlsx) the dataset  to your Colab session.   
Run all cells sequentially to execute the project and view results.
##### Acknowledgments
Google Colab: For providing a seamless Python execution environment.   
Scikit-learn and Pandas: For their robust libraries that made data analysis and modeling efficient.    
Mentors and Peers: For their guidance and support throughout the project.    
