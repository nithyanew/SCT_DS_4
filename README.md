## SCT_DS_Task4  
### Project Title: Traffic Accident Data Analysis (Road, Weather & Time-Based Patterns)

### Description:
This project focuses on analyzing traffic accident data to identify patterns related to **road surface conditions, weather conditions, and time of day**. The analysis was performed using the **US Accidents (March 2023) dataset** in a Kaggle Notebook, and the final notebook was exported for submission.

The objective is to uncover accident trends, contributing factors, and accident hotspots through exploratory data analysis (EDA) and visualization.

### Objectives
- Load and explore the US traffic accident dataset  
- Handle large-scale real-world data efficiently  
- Perform time-based analysis of accidents  
- Analyze the impact of weather and road surface conditions  
- Visualize accident distributions and hotspots  
- Derive meaningful insights from traffic accident patterns  

### Dataset Information
- **Dataset Name:** US Accidents (March 2023)  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/sobhanmoosavi/us-accidents  
- **Size:** ~3 million accident records  
- **Key Features Used:**  
  - `Start_Time`  
  - `Weather_Condition`  
  - `Visibility(mi)`  
  - `Precipitation(in)`  
  - `Start_Lat`, `Start_Lng`  
  - `Severity`

### Data Preprocessing
The following preprocessing steps were performed:
- Loaded the dataset using Kaggle Notebook environment  
- Handled mixed datetime formats in the `Start_Time` column  
- Managed missing values in numerical and categorical features  
- Extracted time-based features such as **Hour** and **Time of Day**  
- Derived **Road Surface Conditions** from weather descriptions  
- Sampled data for visualization to avoid memory issues  

### Analysis Performed
- **Time of Day Analysis:**  
  Studied accident frequency during Morning, Afternoon, Evening, and Night  
- **Weather Condition Analysis:**  
  Identified accident patterns across different weather conditions  
- **Road Surface Condition Analysis:**  
  Classified road conditions as Dry, Wet, Snow/Ice, Foggy, and Storm  
- **Hotspot Analysis:**  
  Visualized accident locations using latitude and longitude data  

### Key Insights
- Most accidents occur during **Afternoon and Evening hours**, indicating peak traffic periods  
- **Dry roads** account for the highest number of accidents due to higher traffic volume  
- **Wet and Snow/Ice conditions** contribute to increased accident risk  
- Accident hotspots are concentrated in **urban and high-traffic regions**  
- Large-scale datasets require efficient preprocessing and sampling strategies  

### Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Kaggle Notebook  
- Google Colab
