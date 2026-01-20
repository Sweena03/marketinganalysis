# Marketing Campaign Performance Analysis
**My first project - A Marketing Data Analysis**

The dataset consists of Marketing Ads Data from different campaigns such as Google Ads and Email from different companies. 

**Objective** - To extract, transform and load the data and perform analysis   
                - Find high performing categories  
                - Understand low performance areas and come up with strategies to increase their overall revenue

**Dataset:**  - https://www.kaggle.com/datasets/guelmaniloubna/marketing-campaign-dataset

**Dataset Description:**     
                
                          - Campaign_ID	- Unique Campaign ID, Identifier
                          - Company	- Name of the Company, Categorical Dimension
                          - Campaign_Type	- Different Compaign Types, Categorical Dimension
                          - Target_Audience	- Categroical Dimension
                          - Duration - Categroical Dimension
                          - Channel_Used	- Categroical Dimension
                          - Conversion_Rate	- Numerical Metric
                          - Acquisition_Cost	- Numerical Metric
                          - ROI - Numerical Metric
                          - Location - Categroical Dimension
                          - Date - Date
                          - Clicks	- Numerical Metric                          
                          - Impressions	- Numerical Metric
                          - Engagement_Score	- Numerical Metric
                          - Customer_Segment - Categroical Dimension

**Created  columns for derived metrics such as** 

                          - CTR - Click Through Rate (helps understand out of all impressions how many clicked)
                          - CPC - Cost Per cLick (How much money was spent towards each click) 
                          - Estimated_Conversions - Approximate number of conversions driven by clicks
                          - Cost Per Conversion - Calculates dollar spent towards each Conversion
