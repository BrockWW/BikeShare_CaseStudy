# Bike Share Case Study

## Description and Findings
We wish to solve the business goal of converting existing "casual rider" customers, riders who only buy single or day trip passes, into "annual members", riders who pay for an annual membership, by implementing new advertising strategies. To do this, we look at historical data from 2024 Chicago, IL, USA that provides trip timing and current membership status data for the fictional Cyclistic bike share company. The data used is real bike share trip data from Motivate International Inc. available under this [license](https://divvybikes.com/data-license-agreement). Using SQL in BigQuery, we imported, cleaned, organized, and filtered the data for analysis, with all steps completed documented in Data_Cleaning_Log. We found the following significant differences between casual riders and annual members in our analysis:
1. There were more overall trips from annual members than casual riders throughout the year and day of the week except weekends during summer.
2. There were many more trips made by annual members during the work week, which points towards annual members using the bike share for traveling to and from work
3. Casual riders on average had longer ride times than annual members.
4. There is a much greater difference in number of trips by membership status during winter, with much fewer monthly casual rider trips and about four times as many annual member trips.
The results of our analysis can be found on Tableau Public [here](https://public.tableau.com/views/CyclisticBike-ShareCaseStudy-GoogleDataAnalyticsProfessionalCertificate/BikeShareDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

Based on these findings we have three recommendations to make to Cyclistic to convert more casual riders to annual members. Each recommendation includes the creation of a new type of membership plan outside of the blanket annual membership and are as follows:
1. Create a weekend (Friday-Sunday) membership plan.
2. Create a spring and summer membership plan.
3. Create a “long-trip” membership plan for riders who have trips over 15 minutes.
Creating one or all of these membership plans will give casual riders the flexibility they want when using the bike-share program while encouraging them to use a membership plan that fits their lifestyle.

## Acknowledgement
This case study was completed as part of the Google Data Analytics Professional Certificate program found [here](https://www.coursera.org/google-certificates/data-analytics-certificate?).
