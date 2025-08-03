### Winning Space Race with Data Science

This project aims to predict the success of Falcon 9 first stage landings using data science and machine learning. The project involved a comprehensive analysis of SpaceX launch data to identify factors influencing landing outcomes and to build a predictive model.

#### Project Goals

The primary objectives of this project were:

  * To accurately predict whether the Falcon 9 first stage will land successfully.
  * To understand how successful landing prediction impacts the determination of launch costs.
  * To explore how this predictive capability could be used by companies bidding against SpaceX.

#### Methodology

The methodology for this project followed these key steps:

1.  **Data Collection & Wrangling:** SpaceX launch data was collected from the SpaceX REST API and Wikipedia tables. The data was then cleaned to handle missing values and a binary "Class" label (1 for success, 0 for failure) was created for machine learning.
2.  **Exploratory Data Analysis (EDA):** EDA was performed using visualizations with Seaborn, Folium, and Plotly Dash, as well as SQL queries.
3.  **Predictive Analysis:** Supervised machine learning models including Logistic Regression, SVM, Decision Tree, and KNN were developed and their hyperparameters were optimized using GridSearchCV. The models were evaluated on an unseen test set.

#### Key Findings

The exploratory data analysis revealed several key insights into Falcon 9 launch success:

  * **Mission Success Rate:** The dataset showed an exceptionally high mission success rate, with 100 successful missions and only 1 failure.
  * **Temporal Trend:** The probability of a successful landing increases with higher flight numbers and showed an overall upward trend from 2013 to 2020.
  * **Launch Site Impact:** Launch sites VAFB SLC-4E and KSC LC-39A demonstrated higher success rates compared to others.
  * **Orbit Type:** Certain orbits like ES-L1, GEO, HEO, and SSO had a 100% success rate, while the SO orbit showed no success.
  * **Payload Mass:** Heavier payloads correlated with increased success rates for Polar, LEO, and ISS orbits.

#### Predictive Model Performance

All four classification models (Logistic Regression, SVM, Decision Tree, and KNN) achieved a consistent classification accuracy of approximately 83.33% in predicting landing outcomes. The confusion matrices for all models were identical, showing that the models mostly correctly predict successful landings.

#### Repository Structure and Resources

The project is structured into several Jupyter notebooks, each covering a different part of the analysis. The links to these notebooks are provided below:

  * **Data Collection (SpaceX API):** [jupyter-labs-spacex-data-collection-api.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/jupyter-labs-spacex-data-collection-api.ipynb) 
  * **Data Collection (Web Scraping):** [jupyter-labs-webscraping.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/jupyter-labs-webscraping.ipynb) 
  * **Data Wrangling:** [labs-jupyter-spacex-Data%20wrangling.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/labs-jupyter-spacex-Data%2520wrangling.ipynb) 
  * **EDA with Data Visualization:** [edadataviz.ipynb](https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/edadataviz.ipynb) 
  * **EDA with SQL:** [jupyter-labs-eda-sql coursera\_sqllite.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/jupyter-labs-eda-sql%2520coursera_sqllite.ipynb) 
  * **Interactive Map with Folium:** [lab\_jupyter\_launch\_site\_location.ipynb](https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/lab_jupyter_launch_site_location.ipynb) 
  * **Dashboard with Plotly Dash:** [spacex-dash-app.py](https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/spacex-dash-app.py) 
  * **Predictive Analysis:** [SpaceX\_Machine%20Learning%20Prediction \_Part\_5.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/SpaceX_Machine%2520Learning%2520Prediction%2520_Part_5.ipynb) 
