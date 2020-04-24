# Welcome to the IDCE30262 Covid-19 Project Repository!
### Date: 4/22/2020
### Authors: Jiang He, Rowan Moody, Qihui Wang, Smruti Naik.



Product Website Link: 
  https://rmoody3.github.io/DWB_Covid-19/



## 1.	Product 1
Our team want to create a web map to help doctor without boards organization to display where potentially need their help. We referred to their activities related COVID-19 in EU and decided to show the information about: coronavirus cases and deaths, long term care residences, acute care hospitals and community health centers in MA. 

### Data used:
•	Town level cases from Mass.gov
https://www.mass.gov/info-details/covid-19-cases-quarantine-and-monitoring
https://www.mass.gov/doc/confirmed-covid-19-cases-in-ma-by-citytown-january-1-2020-april-14-2020/download

•	Long Term Care Residences from MassGIS
https://docs.digital.mass.gov/dataset/massgis-data-long-term-care-residences

•	Acute Care Hospitals from MassGIS
https://docs.digital.mass.gov/dataset/massgis-data-acute-care-hospitals

•	Community Health Centers from MassGIS
https://docs.digital.mass.gov/dataset/massgis-data-community-health-centers


## 2.	Product 2
Our team want to support doctor without boards organization coordinate their future projects in MA. We want to display these information on the map: where their activities happening, when their activities began, the status of each their activities (like how many people they have helped) and estimated end time. Also, we want to show how much area would be benefited from their activities.

### Data used: 
•	Acute Care Hospitals dataset is same as Product 1.

•	Another dataset of their future projects is a makeup sample dataset. The structure of dataset is showing in below:

 1	Activities_id(Text):The id for each activity of doctor without boards organization.
 
 2	Sites_name(Text):The name of each activity site.
 
 3	Address(Text):The address of each activity site.
 
 4	Coordinates_X(Float):The X Coordinates of each activity site.
 
 5	Coordinates_Y(Float):The Y Coordinates of each activity site.
 
 6	Begin_date(Date):The beginning date of each activity.
 
 7	Status(Text):The status for each activity, like pending, processing and completed.
 
 8	Detailed_information(Text):The detailed information for each activity, like how many people the team have helped.
 
 9	Estimated_end(Date):The estimated ending date of each activity.
 
 10	Relative_news_reports(URL):The relative news or reports about each activity from team members or others.


## 3.	Product 3:
Our team want to tell a story about where they are working and the work they are doing, helping the general public understand why it is important.
