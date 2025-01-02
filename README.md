## 🚀 Applied Data Science Capstone

This capstone project serves as the culmination of the [IBM Data Science Professional Certificate](https://www.coursera.org/professional-certificates/ibm-data-science) specialization, synthesizing key concepts and methodologies learned throughout the course. The project allows for practical application and hands-on experience in the field of data science.

### 📄 Project Background

SpaceX, a pioneer in the commercial space industry, has revolutionized space travel by making it more cost-effective. With its groundbreaking Falcon 9 rockets, which cost $62 million per launch compared to over $165 million from competitors, SpaceX has dramatically reduced costs by reusing the first stage of the rocket. The core of this project lies in predicting the likelihood of a successful first-stage landing, based on available launch data. Understanding whether SpaceX can reuse the first stage will have significant implications on launch costs.

By leveraging public information and machine learning models, our goal is to predict whether SpaceX will successfully reuse the first stage of the Falcon 9 rocket. This prediction will help to estimate the cost-effectiveness and overall success of the company's missions.

### 📄 Key Questions to Be Answered

- **How do key factors, such as payload mass, launch site, number of flights, and orbit type, influence the success of the first stage landing?**
- **Has the rate of successful landings improved over time as SpaceX has accumulated more experience?**
- **What is the most effective machine learning algorithm for predicting the binary outcome of first-stage landings (success/failure)?**

### 📄 Methodology

#### 1. **Data Collection Methodology**
   - **SpaceX REST API:** Leveraging the SpaceX API to gather historical data on launches, including rocket details, mission success/failure, payload specifications, and more.
   - **Web Scraping from Wikipedia:** Extracting additional relevant data from Wikipedia, including launch statistics, to supplement our dataset and ensure completeness.

#### 2. **Data Wrangling**
   - **Data Filtering:** Ensuring only relevant data is included, such as successful and unsuccessful first-stage landings.
   - **Handling Missing Values:** Employing strategies like imputation or removal of incomplete records to ensure the integrity of the dataset.
   - **One-Hot Encoding:** Converting categorical variables (e.g., launch site, orbit type) into numerical representations suitable for machine learning.

#### 3. **Exploratory Data Analysis (EDA)**
   - **Visualization Techniques:** Using various visualization tools (e.g., Matplotlib, Seaborn) to uncover patterns, distributions, and outliers in the dataset.
   - **SQL Queries:** Performing SQL-based analysis to segment and aggregate the data for deeper insights into the launch history and success rates.

#### 4. **Interactive Visual Analytics**
   - **Folium Maps:** Creating interactive maps to visualize the geographical distribution of successful and unsuccessful landings, providing context to spatial trends.
   - **Plotly Dash Dashboards:** Developing interactive dashboards that allow for dynamic exploration of the data, including launch site analysis, payload weight, and success probabilities.

#### 5. **Predictive Analysis**
   - **Classification Models:** Building machine learning classification models, including logistic regression, decision trees, support vector machines, and k-nearest neighbors (KNN).
   - **Model Tuning and Evaluation:** Using techniques such as cross-validation, hyperparameter tuning (via GridSearchCV), and performance metrics (accuracy, precision, recall) to ensure the best model selection and optimal predictions.

