## Railroad Incidents Caused by Trespassers
*Data is from The National Response Center from 2017 to 2021*

![Screenshot 2024-01-11 184651](https://github.com/brendonhwang/railroad_incident/assets/155376651/8c384e62-d2af-4637-afd5-b9178d462428)



#### Project Goal

The National Response Center (NRC) is an emergency call center that fields Initial reports for railroad and pollution incidents.   Their online raw data may contain incomplete, inconsistent, and duplicated data due to premature investigation.  I imagined myself as a data analyst hired by the NRC to clean the dirty data and transform them into meaningful information for the stakeholders.

#### PROCESS & RESULT:

Before beginning the project, I researched the NRC and asked many questions. About the presence of dirty data in its data sets and how to identify and clean it? I then created a QA validation list to identify dirty data by reviewing the NRC data dictionary and running QA scripts. The results of this process are included in my QA report. Next, I transformed the raw data into meaningful information and analyzed patterns using the clean data. Finally, I shared my findings and created a visualized dashboard to display various types of data.


#### Data Quality:

*Q: How can data errors be identified, what is the process for cleaning dirty data, and how many records were affected by the data errors?*

To analyze the NRC's data, I first created an error validation list (dirty data) based on the NRC's data dictionary. [CLICK HERE](https://drive.google.com/file/d/1F-RKH58q6bnSUqEnUheCC2nu-hEOZaDu/view?usp=share_link)  
I then developed a QA script with 17 validation queries using MySQL. When running the script the results showed that there were +500 records with dirty data out of +15,000 total records. I then compiled a data quality report by exporting the results [CLICK HERE](https://docs.google.com/spreadsheets/d/1gpAq7NvOR4bu8Pl4Zip4Wf88_ufVIE-Q/edit?usp=share_link&ouid=114709162336788348185&rtpof=true&sd=true)  

<span style="font-family: Arial; font-size: 12px; ;">The file has been converted from Microsoft Excel to a Google Doc.  The original file will be provided upon request.</span>

*Q: What are some ways to improve the quality control (QC) process?*

Some ways to improve the quality of the NRC's data, is enhancing the quality control process by assigning more responsibilities to data analysts. This could include tasks such as cleaning dirty data, providing clean data to the database warehouse, and sharing visualizations with stakeholders. By taking these steps, the NRC could ensure that its data is accurate and reliable. [CLICK HERE](https://drive.google.com/file/d/1VtVgWzTXnYfMN0js0EF3hN65dfs_BwwX/view?usp=sharing)  

#### Analyze Data:
*Q: What is the initial findings, insight of the data, and final thoughts?*

I cleaned and organized the raw data to create a more meaningful view. When faced with an ambiguous question, I broke it down into smaller, more manageable parts and conducted a root cause analysis to identify key factors. Using the results of this analysis, I was able to make recommendations for addressing any issues.

Here is a report on the initial findings, insight of the data, and final recommendations. [CLICK HERE](https://drive.google.com/file/d/1xlliHxO4WYssyZua-Ii3jzPa0-JNQlRW/view?usp=sharing)  

<span style="font-family: Arial; font-size: 12px; ;">The file has been converted from Microsoft Excel to a Google Doc.  The original file will be provided upon request.</span>

#### Data Visualization:
*Q: Is there an effective way to communicate Key Performance Indicators (KPI) to stakeholders?*

Yes, an effective way to communicate Key Performance Indicators (KPI) to stakeholders is through the use of an excel dashboard. This spreadsheet is a useful tool for presenting data analysis findings and telling a data-driven story. It consolidates multiple spreadsheets into one, making it easier to view and understand the KPIs.
 [CLICK HERE](https://drive.google.com/file/d/1ic-kuGQsb3fr1YjrtS3ny6zi9ngD91oC/view?usp=share_link)  

 <span style="font-family: Arial; font-size: 12px; ;">The file has been converted from Microsoft Excel to a Google Doc.  The original file will be provided upon request.</span>

 *Q: Can stakeholders interact with data on a public website?*

Yes, stakeholders can interact with data on a public website through the use of a tableau dashboard. This tool allows for easy navigation and allows stakeholders to find the information they need to make informed decisions.
 [CLICK HERE](https://www.google.com/url?q=https%3A%2F%2Fpublic.tableau.com%2Fapp%2Fprofile%2Fbrendon2981%2Fviz%2FNRCDRAFTVERSION%2FNRC&sa=D&sntz=1&usg=AOvVaw1vDwFSmsEogLKsm3W55AMf)  
 
