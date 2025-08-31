## Health Insurance Cost Prediction (EDA)

### Project Overview
This project performs Exploratory Data Analysis (EDA) on a health insurance dataset of 2,772 individuals.
The analysis explores how demographic and lifestyle factors such as age, BMI, smoker status, and region impact insurance charges.
Findings help insurers design fair pricing models and allow policyholders to understand cost drivers.

### Objectives
Analyze the dataset using univariate, bivariate, and multivariate methods
Identify major factors affecting insurance charges
Visualize relationships between variables using plots and charts
Provide insights for fairer pricing and risk management

### Dataset
Source: [medical_insurance.csv](https://www.kaggle.com/datasets/rahulvyasm/medical-insurance-cost-prediction?)
Rows: 2,772
Columns:
age → Age of the individual
sex → Gender (male/female)
bmi → Body Mass Index (weight/height²)
children → Number of children/dependents
smoker → Smoker status (yes/no)
region → Residential region (northeast, northwest, southeast, southwest)
charges → Health insurance cost

### Exploratory Data Analysis
Univariate Analysis → Age, BMI, charges, smoker distribution, etc.
Bivariate Analysis → Charges vs smoker, charges vs region, BMI vs charges, etc.
Multivariate Analysis → Correlation heatmap, pairplot with smoker hue

### Key Insights
Smoking status is the strongest predictor of charges.
BMI and age also increase charges, especially in smokers.
Region plays a moderate role, while sex has minimal effect.
Charges are highly right-skewed, but log transformation normalizes them.

### Tech Stack
Python,
Pandas,
NumPy,
Matplotlib & Seaborn,
Google Colab

### Google Colab link
https://drive.google.com/drive/folders/1sgZfi-YWc9ntfHBghl5L6UoNdmt-wLvg?usp=sharing
