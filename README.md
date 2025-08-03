### Winning Space Race with Data Science

[cite\_start]This project aims to predict the success of Falcon 9 first stage landings using data science and machine learning[cite: 205]. [cite\_start]The project involved a comprehensive analysis of SpaceX launch data to identify factors influencing landing outcomes and to build a predictive model[cite: 205].

#### Project Goals

The primary objectives of this project were:

  * [cite\_start]To accurately predict whether the Falcon 9 first stage will land successfully[cite: 217].
  * [cite\_start]To understand how successful landing prediction impacts the determination of launch costs[cite: 218].
  * [cite\_start]To explore how this predictive capability could be used by companies bidding against SpaceX[cite: 219].

#### Methodology

[cite\_start]The methodology for this project followed these key steps[cite: 223]:

1.  [cite\_start]**Data Collection & Wrangling:** SpaceX launch data was collected from the SpaceX REST API and Wikipedia tables[cite: 220]. [cite\_start]The data was then cleaned to handle missing values and a binary "Class" label (1 for success, 0 for failure) was created for machine learning[cite: 222].
2.  [cite\_start]**Exploratory Data Analysis (EDA):** EDA was performed using visualizations with Seaborn, Folium, and Plotly Dash, as well as SQL queries[cite: 224].
3.  [cite\_start]**Predictive Analysis:** Supervised machine learning models including Logistic Regression, SVM, Decision Tree, and KNN were developed and their hyperparameters were optimized using GridSearchCV[cite: 224]. [cite\_start]The models were evaluated on an unseen test set[cite: 264].

#### Key Findings

[cite\_start]The exploratory data analysis revealed several key insights into Falcon 9 launch success[cite: 209]:

  * [cite\_start]**Mission Success Rate:** The dataset showed an exceptionally high mission success rate, with 100 successful missions and only 1 failure[cite: 209].
  * [cite\_start]**Temporal Trend:** The probability of a successful landing increases with higher flight numbers [cite: 209] [cite\_start]and showed an overall upward trend from 2013 to 2020[cite: 228].
  * [cite\_start]**Launch Site Impact:** Launch sites VAFB SLC-4E and KSC LC-39A demonstrated higher success rates compared to others[cite: 210, 269].
  * [cite\_start]**Orbit Type:** Certain orbits like ES-L1, GEO, HEO, and SSO had a 100% success rate, while the SO orbit showed no success[cite: 211, 271].
  * [cite\_start]**Payload Mass:** Heavier payloads correlated with increased success rates for Polar, LEO, and ISS orbits[cite: 211, 275].

#### Predictive Model Performance

[cite\_start]All four classification models (Logistic Regression, SVM, Decision Tree, and KNN) achieved a consistent classification accuracy of approximately 83.33% in predicting landing outcomes[cite: 212, 293]. [cite\_start]The confusion matrices for all models were identical, showing that the models mostly correctly predict successful landings[cite: 295].

#### Repository Structure and Resources

The project is structured into several Jupyter notebooks, each covering a different part of the analysis. The links to these notebooks are provided below:

  * [cite\_start]**Data Collection (SpaceX API):** [jupyter-labs-spacex-data-collection-api.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/jupyter-labs-spacex-data-collection-api.ipynb) [cite: 224]
  * [cite\_start]**Data Collection (Web Scraping):** [jupyter-labs-webscraping.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/jupyter-labs-webscraping.ipynb) [cite: 224]
  * [cite\_start]**Data Wrangling:** [labs-jupyter-spacex-Data%20wrangling.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/labs-jupyter-spacex-Data%2520wrangling.ipynb) [cite: 224]
  * [cite\_start]**EDA with Data Visualization:** [edadataviz.ipynb](https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/edadataviz.ipynb) [cite: 229]
  * [cite\_start]**EDA with SQL:** [jupyter-labs-eda-sql coursera\_sqllite.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/jupyter-labs-eda-sql%2520coursera_sqllite.ipynb) [cite: 235]
  * [cite\_start]**Interactive Map with Folium:** [lab\_jupyter\_launch\_site\_location.ipynb](https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/lab_jupyter_launch_site_location.ipynb) [cite: 247]
  * [cite\_start]**Dashboard with Plotly Dash:** [spacex-dash-app.py](https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/spacex-dash-app.py) [cite: 260]
  * [cite\_start]**Predictive Analysis:** [SpaceX\_Machine%20Learning%20Prediction \_Part\_5.ipynb](https://www.google.com/search?q=https://github.com/gauravganeshamin/IBM_Data_Science_Capstone/blob/main/SpaceX_Machine%2520Learning%2520Prediction%2520_Part_5.ipynb) [cite: 268]
