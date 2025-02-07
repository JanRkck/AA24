# AA2024_Groupwork - TheDoubleATeam

## Project Overview
This project was carried out as part of the Master's program in Analytics and Applications at the University of Cologne. Its goal is to offer data-driven insights into the functioning of electric vehicle (EV) charging hubs and to create utilization forecasts. The project follows the CRISP-DM methodology, encompassing data preparation, descriptive analysis, cluster analysis, and the development of predictive models.

## Objectives
### 1. Data Preparation
- Loading and cleaning datasets
- Handling missing and erroneous data

### 2. Descriptive Analytics
- **Temporal Patterns**: Analyze charging behavior over the day, week, and across seasons
- **Key Performance Indicators (KPIs)**: Define and visualize three key time-dependent KPIs
- **Site Characteristics**: Identify differences between public and private charging stations

### 3. Cluster Analysis
- Create clusters to identify typical charging events
- Interpret and name the clusters

### 4. Utilization Prediction
- Develop two models: one based on neural networks and another using an alternative method
- Compare model performance and recommend a suitable method
- Develop a business case based on the findings

## Data Description
The dataset includes charging session information from two locations (public and private), along with supplementary weather data. A detailed description of the dataset fields can be found in the project documentation.

## Results and Insights
The results include:
- Descriptive analyses of charging behavior.
- KPIs for monitoring charging infrastructure.
- Clusters for typical charging events.
- Predictive models for utilization.

## Project Structure
```
📂 AA24/
├── 📁 data/                
├── 01_Data_Prep_Charging.ipynb
├── 01_Data_Prep_Weather.ipynb  
├── 02_Descriptive_Analytics_A.ipynb             
├── 02_Descriptive_Analytics_B.ipynb   
├── 02_Descriptive_Analytics_C.ipynb   
├── 03_Cluster_Analysis.ipynb
├── 04_Utilization_Prediction_Site_1.ipynb            
├── 04_Utilization_Prediction_Site_2.ipynb       
└── README.md               
```


## Authors
This project was conducted by a team of Master's students:
- Peng Zhang
- Xiaofeng Lang
- Mira Mauerer
- Julian Stricker
- Jan Rokicki

## Supervision
- **Supervisor:** Prof. Dr. Wolfgang Ketter
- **Tutor:** Janik Muires (muires@wiso.uni-koeln.de)
