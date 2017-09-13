# Data Analysis on Plankton Study

## Task 1:  List of problems in the provided data.
 
 The data provided is redundant and can be improvised for better results.  There are few other factors we need to consider for better results on the plankton study. Certain errors that I found from the data are as follows. 
* The Column Headers are not consistent across the three files.
* There are blanks on certain fields, which would make the data inefficient to gather results.
* The File naming can be made better by providing versions in that way it would be easy to track and consistent.
* There are varying columns among the three sheets. Its good to maintain consistent column every year.
* It’s clearly mentioned that the scientists collect data twice but nowhere the time it is captured in the spreadsheet.  
We can add time next to the date coulmn.
* There are three samples for each depth on a daily basis, but it is mentioned that readings are taken twice.  There is no understanding on the three readings provided.
* The zoom sheet has the cuni and chippo has separate column whereas the pond excel has species name, i would prefer using just the species name alone.
* The graph plotted in both spreadsheets are for different columns. And the x and y values are not mentioned for these graphs.
* There are few fields highlighted in the spreadsheet and no explanation is mentioned.
* The Units are not mentioned for the required columns.
* The averages are calculated and placed on top of the sheet. But no proper description with respect to headers was provided.

### Additional Ideas: 
> This would be my suggestion to organize the data based on the depth level.The depth should be a separate category to differentiate the samples collected has they are collected from different layers.  Not sure if we can draw conclusion for samples collected from various depths.  In this way we can easily figure out the growth measure like the cuni or Chippo density by looking at the table.


## Task 2:
**File Name:** PlanktonStudy V.0
### Solutions
* The table below has headers that would be consistent column header.
* The above mentioned filename would be consitent file name and can change the version number later on.
* A column to note the tiimings has been added. So that we can have the timings entered on when the data is being captured.
* I have added a column Species Name instead of separate column for Cuni and chippo density and column size.  User can filter data based on the species required.
* The units are mentioned on the column header wherever it is required.
* The graphs can be drawn for the both species separately considering the depth, density or colony size.
* I would have the average being mentioned with the Header as date, the species name and average colony size this should be easy to figure out. 
* The date, depth, time and temp column are in the first of the table has they have the repeated values that makes the work easier for the researcher or the target audience.

**Table:**

| Date | Time | Depth (meters) | Temp (Farenheit or celcius) | Species Name | Colony Size (Millimaters) | Density (Cubic Centimeters or milliliters) | Chla |
|------|------|----------------|-----------------------------|--------------|---------------------------|--------------------------------------------|------|
|      |      |                |                             |              |                           |                                            |      |

**Colony Size Averages:**

| Date       | Species Name | Average Colony Size |
|------------|--------------|---------------------|
| 07/09/2017 | Cuni         | 2.34                |
| 07/09/2017 | Chippo       | 3.45                |
| 07/10/2017 | Cuni         | 3.56                |
| 07/10/2017 | Chippo       | 4.36                |
