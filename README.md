**Crime_data_analysis**

**Introduction**

This project involves creating an interactive dashboard using Power BI to analyze Los Angeles crime patterns from 2010 to the present. The dashboard uses Python Pandas for data cleaning, ensuring standardized formatting, handling missing values, and improving clarity. This tool aids in understanding crime trends, supporting informed decision-making for policymakers and law enforcement.

**Dashboard Insights:**

•	Crime Overview: Information about the overall volume of crimes and the work of law enforcement is provided by highlighting the total number of cases, ongoing investigations, and arrests.

•	Users can drill down into particular regions, weapons, and crime types using interactive slicers.

•	Crime patterns: A heatmap shows the months with the highest levels of criminal activity, while a line chart shows the annual patterns in crime.

•	Location Insights: By highlighting crime hotspots throughout Los Angeles, a density map allows for area-specific research.

•	Crime Types: To determine which types of crimes are most common, users can filter and examine different categories.

•	Weapon Analysis: The most often used weapons are displayed in a pie chart that shows their use in crimes.

The dashboard highlights key insights into crime trends in Los Angeles:
1.	Yearly Trends:
o	2023 recorded the highest number of crimes (234,808 cases), while 2015 saw the lowest (1,703 cases).
o	There was a notable spike in crime occurred in 2016, signaling a need to investigate possible causes such as social factors or policy changes.
2.	Crime Distribution by Areas:
o	The Southwest area reported the most crimes (168,342 cases), followed by the Central area (155,808 cases).
o	The Mission area had the fewest crimes (94,225 cases), indicating a safer region.
3.	Weapons Used:
o	The majority of crimes involved hands, fists, feet, or bodily force (57.86% of cases), reflecting a prevalence of physical altercations.
o	Antique firearms were the least used weapon, with only 13 cases reported.
4.	Number of Victims by Race
o	Hispanic/Latin/Mexican being mostly killed(735972) and Chinese being least killed(5042)

**Data Cleaning with Python Pandas:**

•	Analyzed columns in both datasets to prepare for merging.

•	Standardized column formatting by removing trailing spaces, replacing gaps with underscores, and converting all characters to lowercase.

•	Removed unnecessary columns such as 'crm_cd_1', 'crm_cd_2', 'crm_cd_3', 'crm_cd_4', 'part_1-2', 'cross_street', 'area', 'mocodes', 'crm_cd', 'premis_cd', 'weapon_used_cd', and 'status'.

•	Renamed columns like 'lat' to 'latitude', 'lon' to 'longitude', 'crm_cd' to 'crime_code', 'rpt_dist_no' to 'district_no', 'dr_no' to 'doc_no', and 'vict_descent' to 'vict_race'.

•	Handled missing values by filling nulls, dropped duplicate rows, and corrected data types for date and time columns.

•	Assigned meaningful names to letters in the victim race column for better clarity.




