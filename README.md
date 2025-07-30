# UIS-UNESCO
This repo contains everything needed to pull 157 tables from Institute for Statistics, UNESCO (UIS). The wiki for downloading the data is here: ipbhttps://pardeewiki.du.edu/index.php?title=Institute_for_Statistics,_UNESCO_(UIS)

# Country Concordance 
The file UIS UNESCO contains multiple sheets; the country concordance in sheet Country, OPRI, SDG, SCN-SDG indicaotr ids in their respective sheets, OPRIFORMULAS contains the indicator ids and the formulas needed to calculate the values for the IFs tables, SDG changes include the changes to 6 indicators and therefore the new indicators and forumals, and the DataDict. Before running the code, make sure that all of these sheets are up to date.

# Python Script 
The UIS UNESCO.ipynb is long but separated with markdowns. Tables that need to be multiplied by 0.000001 (series in "Enrollment Headcount" need to  to convert to "Millions") will be calculated in the for loop so there is no extra section for this. 
