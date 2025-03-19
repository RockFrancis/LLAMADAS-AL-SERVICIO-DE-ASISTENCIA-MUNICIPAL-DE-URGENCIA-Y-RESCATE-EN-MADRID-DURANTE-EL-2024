📊 Emergency Service Calls in Madrid (2024)
📂 Project Overview

This project analyzes emergency service calls in Madrid during 2024 using Python. The dataset contains 111,937 records and includes geospatial data. The goal is to clean, process, and visualize the data using interactive and static plots.
📌 Dataset Information

    Source: activaciones_samur_2024.xlsx
    Total Records: 111,937
    Main Variables:
        Date & Time: When the emergency call was made
        Location: District of the incident
        Call Type: Type of emergency reported
        Response Time: Time taken to respond

🛠️ Steps in the Notebook

1️⃣ Data Loading & Exploration

    Read the Excel file into a Pandas DataFrame
    Check for missing values and data types

2️⃣ Data Cleaning

    Remove unnecessary districts (FUERA TERMINO MUNICIPAL, LEGANES, etc.)
    Format date and time columns

3️⃣ Data Visualization

    Matplotlib & Plotly: Create static and interactive plots
    Geopandas: Map emergency calls by district

🔍 Key Findings

    Most emergency calls come from high-density districts.
    Certain areas show higher response times, indicating possible inefficiencies.
    Using interactive maps, we can visualize emergency hotspots.

🚀 Next Steps

    Implement predictive modeling for emergency response times.
    Integrate real-time data for live monitoring.

📢 Contributions & Feedback: Feel free to suggest improvements or test different visualization techniques!


