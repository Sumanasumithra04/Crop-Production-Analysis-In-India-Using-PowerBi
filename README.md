# Crop-Production-Analysis-In-India-Using-PowerBi
For this project dataset was collected from Kaggle https://www.kaggle.com/datasets/pyatakov/india-agriculture-crop-production

The dataset used in this project contains approximately 345,000 records across 12 columns: State, District, Crop, Year, Season, Area, Area Units, Production, Production Units, Yield, Year_transforme, and year-band. Some records had missing (NaN) values in the Production column, which were handled in Power BI by replacing them with 0 using conditional logic in Power Query.

The dataset covers agricultural data from 36 states and 719 districts across 6 different seasons — Kharif, Rabi, Summer, Winter, Autumn, and Whole Year — and includes 56 unique crops. After cleaning, a GROUPBY clause was applied to aggregate production values by district and crop, helping to summarize the production rate effectively.

![General Overview](https://github.com/Sumanasumithra04/Crop-Production-Analysis-In-India-Using-PowerBi/blob/694f12b06768d8806a8da92bd42681c5591e890d/General%20Overview.png)
![State wise](https://github.com/Sumanasumithra04/Crop-Production-Analysis-In-India-Using-PowerBi/blob/694f12b06768d8806a8da92bd42681c5591e890d/State%20Wise.png)

The Power BI report comprises two main pages:

Page 1 presents key indicators such as total states, total districts, total cultivated area, and total production. It features visuals like donut charts, year sliders, and season filters to offer a high-level overview of agricultural distribution across India.

Page 2 provides detailed crop-level analysis, illustrating production trends over the years through line graphs, seasonal distribution using pie charts, and a table highlighting crops based on total production.

![example](https://github.com/Sumanasumithra04/Crop-Production-Analysis-In-India-Using-PowerBi/blob/8b6efb57546c6b549d0af165b08c4e8c2d1e1d5d/Example.png)
![example](https://github.com/Sumanasumithra04/Crop-Production-Analysis-In-India-Using-PowerBi/blob/8b6efb57546c6b549d0af165b08c4e8c2d1e1d5d/example%201.png)





