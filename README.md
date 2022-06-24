#Project name: 
-------------
COVID-19 GLOBAL INSIGHTS

#Project objective: Problems to Analyze
-----------
The global virus COVID-19(The coronavirus disease) is a communicable respiratory disease, the novel disease emanated from an Asian country particularly in China(2019) and the virus spread across the globe in the year 2020 infecting humans, both young and old. Different measures were taken by world countries in limiting the fatality rate of the novel disease and a special thanks to the carers who dedicated their time and expertise in ensuring those infected received medical attention.
Data are recorded daily,monthly,yearly for confirmed cases, death cases and people who recovered from the the deadly virus and data still keeps coming in till date. I'm an aspiring data analyst currently enrolled in an online learning platform NG30daysoflearning and this analysis was done to have an insight using the data provided to analyse the confirmed cases, death cases and fatality rate for all countries with respect to the days,months and years.

#Data Sourcing:
---------
The data used to derive these insights were scraped from the web on COVID19 GitHub data-https://aka.ms/30DLCOVID19GithubData and the analysis was completed using Microsoft Excel.

#Data Transformation:
------------
The data was loaded from the covid19 GitHub website and copied the source code into Microsoft Excel in the following order; confirmed cases,Death and Recovered cases.
The data was then opened in power Query in order to transform and clean the data.

#The followimg procedure ensued;
--------
I Changed the query name, edited the source to remove the column load limit in order to enable update. Made first row as column header and selected state/province, country/region, long, lat then unpivot other columns.
Made sure to Delete Attribute, changed data types and renamed columns from value to confirmed. 
I duplicated the query and then changed the source with deaths and recovery in other to apply the previous changes then renamed their columns to death and recovered. Also renamed the query name as appropriate. 
On home tab, I merged query as new for confirmed and death by clicking on provincce, country and date. 
I Combined recovered and renamed as consolidated data then proceeded to remove unwanted columns such as long, lat, province and Changed the data type for date and worked on pivot tables and charts.

#Findings:
-----
