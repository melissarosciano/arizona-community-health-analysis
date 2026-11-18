### **Arizona Community Health Outcomes \& Disparities Analysis**

### 

Tools: Power BI Desktop, Power Query, DAX



Data Source: Centers for Disease Control and Prevention (CDC), PLACES: Local Data for Better Health, 2025 Release.



Data Description: County-level, age-adjusted prevalence estimates for diagnosed diabetes and obesity among adults aged 18 and older. The 2025 release uses 2023 Behavioral Risk Factor Surveillance System (BRFSS) data for these measures, along with U.S. Census Bureau and American Community Survey data.



Geographic Scope: All 15 Arizona counties.



Data Source Reference: https://www.cdc.gov/places/



Methodology Reference: https://www.cdc.gov/places/methodology/

Geographic Scope: 15 Arizona Counties



##### Project Overview



Developed an interactive Power BI report to examine geographic differences in diagnosed diabetes and obesity prevalence across Arizona’s 15 counties.



The project explores variations in chronic disease burden, compares county-level estimates against statewide county-average benchmarks, and investigates the relationship between obesity and diagnosed diabetes prevalence.



##### Analytical Objectives

##### 

\* Compare age-adjusted diabetes and obesity prevalence across Arizona counties.

\* Identify counties with estimates above or below the unweighted county average.

\* Evaluate the linear relationship between obesity and diabetes prevalence.

\* Present results through interactive visualizations and comparative indicators.



##### Data Preparation and Analysis



Imported CDC PLACES data into Power BI Desktop and used Power Query to filter records by geography, health measure, and prevalence estimate type.



Developed DAX measures to calculate county averages, fixed comparison benchmarks, percentage-point differences, and Pearson’s correlation coefficient.



Created three interactive report pages: Community Health Overview, County Comparison, and Health Relationships.



##### Key Findings



1\. Diabetes prevalence



The unweighted average of county-level age-adjusted diagnosed diabetes prevalence estimates was approximately 11.0%.



2\. Obesity prevalence



The unweighted average of county-level age-adjusted obesity prevalence estimates was approximately 33.7%.



3\. Geographic disparities



Apache County’s estimated diabetes prevalence was 4.3 percentage points above the Arizona county-average benchmark. Its estimated obesity prevalence was 2.3 percentage points above the corresponding benchmark.



4\. Relationship between diabetes and obesity



Pearson’s correlation coefficient was 0.66, indicating a moderately strong positive linear association between county-level estimates of diagnosed diabetes and obesity prevalence.



##### Methodological Limitations



CDC PLACES produces model-based prevalence estimates. The analysis is descriptive and does not establish causation, individual-level relationships, or statistical significance.



County-average benchmarks are unweighted means of geographic estimates, not population-weighted statewide prevalence rates.



##### Technical Skills Demonstrated



Power Query data preparation, DAX calculations, filter context management, conditional formatting, interactive slicers, benchmark comparisons, scatter plots, and analytical data storytelling.

