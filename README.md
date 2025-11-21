# Referrals-Dashboard
Example of a real dashboard showing analysis of data for referrals to a medical practice, utilized by C-suite executives.

This is data analysis of incoming patient referrals to a gastroenterologist practice. Data for this report has been generated using random numbers and names to ensure confidentiality although formats of data have remained the same to best replicate real development of this dashboard. 

Data Comes from an Electronic Medical Records system which outputs as a schedule audit report for 13 months of data. This data contains appointment time, appointment creation time, and other appointment details including activity type, status, and most importantly for this analysis, it includes referring physician data. (Example Referral Data Sheet.xlsx)

Data is cleaned and staged into a staging file using PDS DASH. (PDS DASH is used purely as a tool for automation of this dashboard. All cleaning and staging of this data is done in Excel with PDS DASH facilitating it.) (Example Referral Dashboard Staging.xlsx)

The staging file is then used to generate the data visualization. PDS DASH is also used as a tool for automating the creation of the data visualizations. (Example Referral Dashboard.xlsx)

Some key metrics conveyed by this dashboard are the monthly completed referrals as well as monthly received referrals compared to the same month in the prior year. Other important metrics on this dashboard include the top 15 referring providers as well as practices. This data is shown as YTD data on a heatmap table to show the top providers that have referred patients to our practice as well as the top practices that have referred to the practice. 

This data is vital to ensure the practice continues to grow as this data is used to see what practices or providers we should invest in building stronger relationships. Although the data in this example is randomized so it does not demonstrate real trends in the growth of the practice, this dashboard has successfully been utilized to target specific practices and results were reflected in the data. This dashboard has also proven useful in identifying problem areas in our operations by isolating outliers and other problematic data. 



