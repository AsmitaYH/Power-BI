
# Healthcare analysis

This dashboard helps the hospital analyze attributes affecting the patients' length of stay (LOS) and cost and factors contributing to hospital differences.

Dashboard link: 
https://tunepal-my.sharepoint.com/:u:/g/personal/asmita_762416_puc_tu_edu_np/EQy6i8rCh4JKq5IlCDkEdAwBT73yzlTNb_HMYD9ChjIIrA?e=GoMtng

Steps followed:
Data on all hospital stays in a single year for elective hip replacement surperies.

Step 1: Load data into Power BI Desktop followed by some exploratory analysis of data, dataset is csv file.

Step 2: Profile entire dataset to investigate the column distribution.

Step 3: Remove rows where procedure description is not "HIP REPLACEMENT, TOT/PRT".

Step 4: Create a measure called "Total Hospital".

Step 5: Number of hospitals by health_service_area.

Step 6: Visulaize the number of discharges by gender in a new chart by percentage.

Step 7: Modify visualization by age groups.

https://github.com/AsmitaYH/Power-BI/issues/1

Step 8: Create a measure called Average LOS Days and a new page "LOS".

Step 9: Create visualizations to assess avergae LOS day by age group and gender.

Step 10: Create a new page called "Hospital Comparison" and a chart displaying both total discharges by hospitals and average LOS days.

Step 11: Create a measure that calculates the count of surgeons.

Step 12: Integrate the total surgeon count into main chart of LOS nad discharges by hospital as a tooltip.

Step 13: Create a new page "Cost" to calculate average cost per discharge.

Step 14: Assess the metric by hospital name and health_service_area.

Step 15: Add conditional color formatting to display cells with a value greater than or equal to the overall state average ($20,910).

Step 16: Create two measures, one for Average cost per discharge and another for average LOS days.

Step 17: Create a measure that calculates the percentage difference in Average cost per discharge.

Step 18: Create a percent variance calculation for average LOS days vs state average.

Step 19: Create a scatter chart that displays Average LOS Days vs Average Cost per Discharge.

Step 20: Use DAX function SUMMARIZECOLUMNS() to create a new table called surgical_program_volume_summary.

Step 21: Update data model to ensure hospital_discharges table joins with surgical_program_volume_summary on facility name.

Step 22: Create a new column called "Total Discharges (bins)" to group the values in bin size of 200.

Step 23: Create a "Key Influencers" page to see differnt root variables. 
         Risk of mortality
         Severity of illness description
         Diagnosis description
         Patient disposition
         gender
         Age bins
         Surgical program size
         Health service area

Step 24: Integrate existing visuals and customize slicer interactions to create an overview.


LOS Comparison Dashboard
https://github.com/AsmitaYH/Power-BI/issues/2

Cost Comparison Dashboard
https://github.com/AsmitaYH/Power-BI/issues/3

Hospital Profile
https://github.com/AsmitaYH/Power-BI/issues/4#issue-3088436705

