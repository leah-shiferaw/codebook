# codebook

#This was an assignment as part of a Data Analysis course at AU's School of International Service. 
You can find the initial dataset here: https://eventdata.parusanalytics.com/data.dir/atrocities.html

A brief itemized list of some of the work conducted on the data set is also copied below:

•	Changed the spaces to underscores
•	Re-ordered variables to: Country, Event_Type, Start_Day, Start_Month, Start_Year, End_Day, End_Month, End_Year, Perp_State_Role, Deaths_Number, Injured_Number, Organization_of_Violence, Description, Primary_Source
•	Recoded the Start_Month and End_Month from numeric values to shortened abbreviations of the month
•	Removed the character values (“dozens”, “scores”, “hundreds”, etc.) from Deaths_Number and Injured_Number
•	Renamed the following variables: 
  o	Event_Type to Event
  o	Deaths_Number to Deaths
  o	Injured_Number to Injured
  o	Organization_of_Violence to Method
•	Changed the “99” values in Start_Day, Start_Month, Start_Year, End_Day, End_Month, and End_Year to NA’s

