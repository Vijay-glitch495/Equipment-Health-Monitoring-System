# Equipment-Health-Monitoring-System
![image](https://github.com/Vijay-glitch495/Equipment-Health-Monitoring-System/assets/108282191/0ef3bea5-4e99-4184-9f19-4a32652dd4ab)

## Overview:
This project focuses on predictive maintenance in industrial settings, specifically classifying types of failures based on sensor data. Using Jupyter Notebook for data analysis and modeling, Streamlit to deploy, and CRISP-DM for project organization, we aim to enhance machine reliability and reduce downtime through maintenance strategies.

## Objectives:
Classify types of failures using machine learning models.

## Data Source:
The analysis utilizes the Predictive Maintenance Dataset (AI4I 2020), containing sensor readings and failure information from industrial equipment.

## Project Structure:
<li>Jupyter Notebook: Contains data preprocessing, exploratory data analysis (EDA), modeling, and evaluation using Python libraries such as pandas, numpy, and scikit-learn.</li>
<li>CRISP-DM Framework: Organizes the project into phases: business understanding, data understanding, data preparation, modeling, evaluation, and deployment.</li>
<li>Streamlit App: Deploys the trained model for interactive predictions and analysis.</li> 

## Technologies Used
<li>Pandas: For data manipulation and analysis.</li>
<li>NumPy: For numerical operations.</li>
<li>Matplotlib: For data visualization.</li>
<li>Seaborn: For advanced data visualization.</li>
<li>Plotly Express: For interactive data visualization.</li>
<li>Scikit-Learn: For machine learning model implementation.</li>
<li>Imbalanced-Learn (ImbPipeline): For handling imbalanced datasets.</li>
<li>Pickle: For saving trained models.</li>
<li>Streamlit: For creating a web application interface.</li>

## Processes and Steps

## 1. Data Preprocessing
<li>Loading the Data: Importing the dataset and checking for duplicates and missing values.</li>
<li>Data Transformation: Using ColumnTransformer and Pipeline for feature handling.</li>
<li>StandardScaler: Scaling numerical features.</li>
<li>OneHotEncoder: Encoding categorical features.</li>

## 2. Exploratory Data Analysis (EDA)
### Visualization: Plotting data to understand distributions and relationships.
<li>Proportion of Failure Types:</li>
This section displays the image showing the different types of failures and their proportions.
<img src="https://github.com/Vijay-glitch495/Equipment-Health-Monitoring-System/blob/main/images/Proportioin%20types.png?raw=true" alt="dataub" width=450/>
<li>Proportion of Failures:</li>
This section displays the image depicting the overall proportion of failures.
<img src="https://github.com/Vijay-glitch495/Equipment-Health-Monitoring-System/blob/main/images/proportion%20of%20failure.png?raw=true" alt="dataub" width=450/>
<li>Correlation Matrix:</li>
This section displays the correlation matrix image, which helps in understanding the relationships between different variables.
<img src="https://github.com/Vijay-glitch495/Equipment-Health-Monitoring-System/blob/main/images/correlation.png?raw=true" alt="dataub" width=450/>
<li>Class Distribution:</li>
This section displays the image showing the distribution of different classes in the dataset.
<img src="https://github.com/Vijay-glitch495/Equipment-Health-Monitoring-System/blob/main/images/class%20distribution.png?raw=true" alt="dataub" width=450/>


### Dimensionality Reduction: Applying PCA to reduce feature dimensions while retaining variance.
<li>PCA Explained Variance:</li>
This section displays the image illustrating the explained variance of different PCA components.
<img src="https://github.com/Vijay-glitch495/Equipment-Health-Monitoring-System/blob/main/images/PCA%20Expalined%20variance.png?raw=true" alt="dataub" width=450/>
<li>PCA Components:</li>
This section displays the image showing the PCA components
<img src="https://github.com/Vijay-glitch495/Equipment-Health-Monitoring-System/blob/main/images/PCA%20components.png?raw=true" alt="dataub" width=450/>

## 3. Model Training
<li>Baseline Model: Initial model training using RandomForestClassifier.</li>
<li>Handling Imbalanced Data: SMOTE for over-sampling the minority class, Tomek Links for under-sampling the majority class, and NearMiss for focusing on the most informative samples.</li>

## 4. Model Evaluation and Fine-Tuning
<li>Metrics Evaluation: Calculating accuracy, recall, precision, and F1 scores.</li>
<li>Hyperparameter Tuning: Using GridSearchCV for optimizing model parameters.</li>

## 5. Model Interpretation
<li>Confusion Matrix: Visualizing model performance.</li>
<li>Feature Importance: Understanding feature impacts on predictions.</li>

## 6. Deployment
<li>Saving the Model: Using pickle to save the trained model.</li>
<li>Creating a Web Interface: Implementing with Streamlit to make predictions interactively.</li>

## 7. Conclusion and Future Work
<li>Summary of Results: Summarizing model performance and capabilities.</li>
<li>Future Enhancements: Suggesting improvements for the model and its applications.</li>

## Streamlit_app📱⚙️: 
https://equipment-health-monitoring-system.streamlit.app/
