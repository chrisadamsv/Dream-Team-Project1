# Storm Surge - How Hurricanes Affect Local Economies
 ## Introduction
   Hurricanes have long plagued the south-east United States, causing grief and untold damage to both those unfortunate enough to be in their paths and to the country as a whole. Due to the affects of climate change these affects are being compounded as rising temperatures cause them to grow stronger and more frequently. But what are some of the figures attached to these disastrous phenomena? How do they actually affect local economies in the United States?
   
## Hypothesis
   We can expoect to see that housing prices increase after a hurricane compared to the national average. Hurricanes bring a lot of destruction, thus making it more expensive to own a home. ALso, the scarcity of livable properties post-disaster and the urgent need for housing create a competitive market that pushes prices upwards. We also expect there to be an increase in jobs and possibly income, due to the increase in jobs to help rebuild the area. Job creation in industries such as construction, engineering, and government-sponsored disaster relief programs will likely be substantial.


## Methods
   To gather our data, we assembled a dataset containing the Housing Price Index from the FHFA, median income from the BEA, and jobs count from the BEA for each county from the years 1980 to 2023. From there, we analyzed the changes for each feild accross a five year period around each instance. We then isolated the counties that have been directly affected by hurricanes using data from the National Hurricane Center. We specifically puled storms where significant damage was reported so that less impactful storms will not skew the data. From there, we can see what happens on average when a hurricane strikes an area compared to its state and national averages.

## Data Analysis
### 1. What areas are most affected by hurricanes?
According to our research, Florida receives the majority share of hurricane landfalls at about 27%. This is to be expected since Florida also has the largest coastline of any continental state, as well as being in the primary region necessary for tropical development. Florida is also the only state to be directly impacted by Category 5 hurricanes in modern history; Andrew and Michael in 1992 and 2018, respectively.

![landfall_map](https://github.com/user-attachments/assets/f3e9d744-3307-42cd-98dc-34a94de277ec)
![state_pie](https://github.com/user-attachments/assets/8e39fd98-69bc-4f63-bd4a-08f2de5d6b16)

### 2. How do hurricanes affect the price of homeownership?
Trends in Housing Price Indices (HPI) show an increase the year following a major hurricane and then proceeds to decline in subsequent years; meanwhile per capita income of landfall afflicted counties tends to fluctuate to a far greater degree than the national or even state averages, but following a similar pattern of a rise in the year of a hurricane, then a decrease and increase in the following years.

![HPI_line](https://github.com/user-attachments/assets/2db73ba0-7bab-4770-8fae-13ca42ac1135)
![HPI_bar](https://github.com/user-attachments/assets/030c95c0-cc86-4900-afd5-05215e769902)

### 3. How do hurricanes affect median income?
The mean overall income between county and the nation and respective state does not seem to follow any distinct pattern. The lines have a very particular "M" shape that they all follow, leading to only small variations in true difference as shown by the bar graph. Only a 1.5% a most between the 4 year period of and following a hurricane.

![income_line](https://github.com/user-attachments/assets/6f4e8f8e-33b9-4ef1-b7f9-d584cd6f8754)
![income_bar](https://github.com/user-attachments/assets/ab9109c3-5831-4188-8989-21034314aec6)

### 4. How do hurricanes affect jobs?
In the year of a hurricane, landfall counties see a lesser increase percentage in jobs but is followed by an increase in the following years far exceeding the national average. All though the actual differences themselves are not significant, the county line follows a distint pattern while the state and nation have a similar shape. 

![jobs_line](https://github.com/user-attachments/assets/5c011494-802d-4429-8d9c-200e9f21a3e6)
![jobs_bar](https://github.com/user-attachments/assets/9a40745b-9915-452f-87c7-cb174a3bbfef)

### Conclusions
   While hurricanes are costly and often times disastrous for everyone, our research shows generally positive economic trends for those involved and ultimately, like a fire or other natural disasters, can lead to a stronger community through rebuilding and recovery. Further research will show more specifically how these changes occur. Despite any positive economic output that hurricanes may create, they are extremely dangerous storms that should never be taken lightly. The loss of life and destruction they cause can never be undone. 

### Next Steps
   In the future, we would like to analyze what happens over a longer period of time to meausure any long term affects. We would also like to analyze outside factors better to see if they have any undue influence on these metrics. 
   Another important factor to address is the limitations in the dataset. In the future, the metrics should be broken up to better analyze different variables, such as analyzing whuch jobs are affected in an area rather than just all jobs. Breaking down these variables can help paint a better picture of what happens to a state and local economy after a hurricane strike.
   
### Resources
- Hurricanes by costliness:
    https://www.ncei.noaa.gov/access/billions/dcmi.pdf

- List of US hurricane landfalls:
    https://www.aoml.noaa.gov/hrd/hurdat/UShurrs_detailed.html

- FHFA Housing Price Index data:
    https://www.fhfa.gov/data/hpi/datasets

- Bureau of Economic Analysis: 
   
   - Chart for per capita income for every County 1980-2023:
     https://apps.bea.gov/api/data?&UserID={KEY}&method=GetData&datasetname=Regional&TableName=CAINC1&LineCode=1&Year=ALL&GeoFips=COUNTY&ResultFormat=json

   - Chart for total jobs for every county 1980-2023:
     https://apps.bea.gov/api/data?&UserID={KEY}&method=GetData&datasetname=Regional&TableName=CAINC30&LineCode=240&Year=ALL&GeoFips=COUNTY&ResultFormat=json
