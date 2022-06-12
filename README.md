#     🚀 💻 SpaceX Rocket Landing Predictions 💻 🚀 

<p align="center">
  <img src="https://img.shields.io/badge/Python-3670A0?&logo=python&logoColor=ffffff" /> 
  <img src="https://img.shields.io/badge/NumPy-%23013243.svg?&logo=numpy&logoColor=white"/> 
  <img src="https://img.shields.io/badge/pandas-%23130754.svg?logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-%23F89939.svg?&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-%23F37725.svg?&logo=jupyter&logoColor=white"/>
</p> 


## 🌍 Introduction  🌎
In this repository you will find all of the necessary Python files and Jupyter Notebooks I used to finish the capstone Project of the IBM Data Science Course. Object of this project is SpaceX. SpaceX is a leading designer and manufacturer of rockets and spacecraft. According to the website of SpaceX the cost of their rocket launches is $62 million, while other providers cost upwards of $165 million per launch. Much of the savings is because SpaceX can reuse the first stage of the rocket. However sometimes, the first stage does not land or cannot be recovered. Therefore if we can determine if the first stage will successfully land, we can determine the cost of a specific launch. 

In this project I'll collect and process raw data from a variety of sources, explore the data using different visual analytics tools, and build a predictive model to determine wheter the first stage of the SpaceX Falcon 9 rocket will land successfully for other companies to bid on the outcome more informed.


## Table of Contents 👾
### [Data Collection](https://github.com/TonyGlimm/Applied-Data-Science-Capstone/tree/master/01%20-%20Data%20Collection) and [Webscraping](https://github.com/TonyGlimm/Applied-Data-Science-Capstone/tree/master/01%20-%20Data%20Collection)
- Collected launch data using the SpaceX REST API.
- Scraped additional data from the web using Python's `BeautifulSoup` package.

### [Data Wrangling](https://github.com/TonyGlimm/Applied-Data-Science-Capstone/tree/master/02%20-%20Data%20Wrangling)
- Preprocessed and cleaned the data set to begin data exploration.

### [Data Visualization/EDA](https://github.com/TonyGlimm/Applied-Data-Science-Capstone/tree/master/03%20Exploratory%20Data%20Analysis)
- Explored the relationships between different sets of features in the data set and identified important variables in predicting rocket launch successes.

### [Geospatial Analysis using Folum and Launch Success Rate Dashboard](https://github.com/TonyGlimm/Applied-Data-Science-Capstone/tree/master/04-Interactive%20Visual%20Analytics)
- Created interactive leaflet maps using `folium` and analyzed existing launch site locations to identify geographical trends in the data.
- Developed an interactive Plotly Dash app to analyze success rates based on launch site location and payload weight.

### [Predictive Modelling](https://github.com/TonyGlimm/Applied-Data-Science-Capstone/tree/master/05%20-%20Predictive%20Analysis%20(Classification))
- Fit several classification models, including a Support Vector Machine, Logistic Regression, Decision Tree, and K-Nearest Neighbors model.
- Tuned model parameters using cross-validation and predicted whether the first stage of a rocket launch will land successfully 


<p align="center">
  <img src="https://media.designrush.com/inspiration_images/134929/conversions/_1512513081_152_ibm-mobile.jpg"/>
</p>
