#   SpaceX Falcon 9 Launch Success Prediction

This project focuses on predicting the **first-stage landing success** of SpaceX Falcon 9 rockets using real-world launch data. First-stage reusability is crucial for reducing spaceflight costs, and this project explores how data science and machine learning can help estimate landing outcomes.

---

##   Project Structure

| File / Notebook | Description |
|-----------------|-------------|
| **1_Data Collection API.ipynb** | Collected SpaceX launch data using the official REST API. |
| **2_Data Collection with Web Scraping.ipynb** | Scraped mission details from Wikipedia to enrich the dataset. |
| **3_Data wrangling.ipynb** | Cleaned, merged, and transformed raw data for analysis. |
| **4_EDA with SQL.ipynb** | Performed exploratory data analysis using SQL queries. |
| **5_EDA with Visualization.ipynb** | Visualized trends and correlations using Matplotlib and Seaborn. |
| **6_Interactive Visual Analytics with Folium lab.ipynb** | Built interactive geospatial launch maps using Folium. |
| **7_spacex_dash_app.py** | Developed an interactive dashboard with Plotly Dash. |
| **8_Machine Learning Prediction.ipynb** | Built machine learning models (Logistic Regression, SVM, Decision Tree, KNN). |
| **Capstone_Presentation.pdf / .pptx** | Final project presentation summarizing the workflow and results. |

---

##   Project Objectives

- Identify factors influencing SpaceX Falcon 9 first-stage landing success.  
- Perform end-to-end data processing: collection → cleaning → EDA → modeling.  
- Build interactive dashboards and maps for visual analytics.  
- Develop ML models to predict landing success based on mission features.

---

##   Tech Stack

**Languages:** Python, SQL  
**Libraries:** pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Plotly, Folium  
**Tools:** Jupyter Notebook, Plotly Dash, REST API, Web Scraping  
**Data Sources:** SpaceX API, Wikipedia

---

##   Machine Learning Models Used

- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree Classifier  
- K-Nearest Neighbors (KNN)

The models were trained on key features like launch site, orbit type, payload mass, and booster version to predict landing outcomes.

---

##   Interactive Dashboard

The Plotly Dash dashboard provides:

- Launch success rates by site  
- Correlation between payload mass and landing outcome  
- Booster version performance  
- Interactive charts and visuals for mission insights 
