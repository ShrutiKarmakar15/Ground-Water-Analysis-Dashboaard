# Groundwater Analysis of Samoda Watershed 2024 -Dashboard

### Dashboard Link : https://nitrracin-my.sharepoint.com/:u:/g/personal/mrisahu_it_nitrr_ac_in/ESvtvqgO-6dAoMW6CQ9Xw8EBYEBWvazl2bH2fJfwosoKLQ?e=jhaPG8

## Problem Statement


This dashboard provides insights into groundwater levels, quality, and usage patterns to help stakeholders such as policymakers, researchers, and local governments make data-driven decisions.This study assesses the groundwater quality in the Samoda region of Chhattisgarh, India, by analyzing data from 45 sampled sites. Key parameters, including Water Quality Index (WQI), nitrate, fluoride, and pH levels, were measured to evaluate water suitability for consumption. 


 By empowering local authorities with data-driven insights, this study aims to help secure safer groundwater for communities and support sustainable resource management across similar regions.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Visualization tools used to study the data.

        1. Bar Chart: Water Quality Index (WQI) vs. Sample Location : 
        • X-Axis : Sample No (or Sl No),
        • Y-Axis: WQI 
        • Purpose: Identify which locations have water that could pose a health risk based on the Water Quality Index. 
        Snap of new calculated column ,

![Screenshot 2024-11-04 151742](https://github.com/user-attachments/assets/3aa18f06-617a-40e3-bb0f-179657377f60)

        2. Pie Chart: Water Suitability 
        • Categories: Suitable/Unsuitable 
        • Values: Count of records 
        • Purpose: Visualize the proportion of water samples that are classified 
        as suitable versus unsuitable for human consumption.
        Snap of new calculated column ,

![Screenshot 2024-10-20 233523](https://github.com/user-attachments/assets/5d65bacc-4690-490f-8986-8a03678c352d)

        3. Line Chart: Nitrate (NO3) and Fluoride (F) Trends 
        • X-Axis: Sample No 
        • Y-Axis: Multiple lines for NO3 and F 
        • Purpose: Nitrate and Fluoride levels in water are linked to health 
        issues like methemoglobinemia (blue baby syndrome) and skeletal fluorosis. This chart shows where these chemical levels exceed safe limits. 
        Snap of new calculated column ,

![Screenshot 2024-10-20 233547](https://github.com/user-attachments/assets/0eebee38-d76f-435f-9de6-65b505b2e3bc)

        4. Scatter Plot: pH vs. each sample  (NO3, Cl, etc.) 
        • X-Axis: pH 
        • Y-Axis: sample  
        • Purpose: we know that water with pH around 7 is neutral , the plot 
        shoes the samples that comes under the neutral range .  
        Snap of new calculated column ,

![Screenshot 2024-10-20 233603](https://github.com/user-attachments/assets/709fea93-5011-4852-8dcf-3cd91b4ae49d)

        5. Key Influencers Visual for Health Impacts: 
        • Purpose: Discover what factors influence whether water is classified as 
        Excelent, Good  and poor. 
        • How to create: 
        1. Use the Key Influencers visual. 
        2. Analyze: Excelent , good , poor. 
        3. Explain by: Include chemical parameters like Ca, Cl, F, NO3, pH. 
        4. This will show which factors (e.g., high nitrate or low pH) most   
        strongly influence water unsuitability, providing insight into health
        risks.
        Snap of new calculated column ,

![Screenshot 2024-11-05 224340](https://github.com/user-attachments/assets/cd57ae79-e995-496a-a2aa-a89ba4124889)


# Report Snapshot (Power BI DESKTOP)

 
[Mineral Report on ground water.pdf](https://github.com/user-attachments/files/18135373/Mineral.Report.on.ground.water.pdf)

Following inferences can be drawn from the dashboard:

        1. Water Quality Index (WQI) Analysis: The "Average of WQI by Sample Number" chart shows variability in water quality across different samples. Specific samples appear to have notably higher or lower WQI scores.

        2. Suitability of Groundwater: Approximately 66.67% of the samples are marked "Suitable" for use, while 33.33% are labeled "Unsuitable."
        
        3. NO₃ and Fluoride Levels: The "NO₃ and F by Sample Number" chart shows concentrations of nitrates (NO₃) and fluorides (F). Some samples might exceed recommended levels, potentially impacting suitability.
        4. Key Influencers on Water Type Status: Lower chloride (Cl) and nitrate (NO₃) levels significantly increase the likelihood of the water type being classified as "Excellent."
        The dashboard suggests a strong correlation between reduced Cl and NO₃ levels and water quality improvement.
        5. pH Analysis: The pH range across samples is visualized, likely falling within regulatory standards for potable water.

