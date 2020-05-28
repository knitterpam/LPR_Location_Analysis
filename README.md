# Immigration Judge Analysis

## Analysis of Immigration Judge Decisions by Background and State
### Motivation
Since 2013 I have transcribed immgration hearings for a company contracted to the Department of Justice (DOJ).  When I started this work, there were not many immigration judges (IJs) in the system and they were located primarily in the states with the largest number of cases (New York, Texas, California, Florida) with a small number sprinkled throughout the other states.  The system was very bogged down and cases were often scheduled years out due to the rising number of immigrants and small pool of IJs. After the most recent President was elected, changes were made to the entire immigration process in order to increase the speed at which cases were heard and finalized.  I noticed that many of the new IJs hired had previously worked as trial attorneys for the Department of Homeland Security (DHS).  I imagine this made onboarding the new IJs much quicker, as these former lawyers were already familiar with the entire process.  I started to wonder if there might be a change in the ratio of denials/grants if they had previously worked for the government.  I also wondered whether the backlog of cases had improved with the hiring of more IJs to handle the case load.  Then I wanted to see which states had the highest and lowest number of cases and backlog.

I wanted to analyze IJ decisions and answer the following questions:

 What does the current backlog and number of cases look like with the increase of new IJs hired?  Which states have the highest and lowest number of cases and length of backlog?
 How do decisions vary by judge?
 Is there a correlation between cases held by video conference and cases denied due to lack of personal contact between the alien and the IJ?
 Is there a relationship between prior legal background of an IJ and percent of asylum denials/grants?

### Data
To answer these questions, I used immigration data for XXXX (Year), as well as IJ information scraped from text on a site compiled by Syracuse University. This data was made available from the US goveenment at opendata.gov. I aggregated the data by state and by IJ.

### Analytical Approach
To answer the question of prior legal background, I scraped the information (or I created a table containing the presence of a DHS background) from the Syracuse University list of IJ information. I then created a bar graph showing the percentage of cases denied or granted by each judge pulled from immigration data provided by the US government. ranked each region by the group rate for each month and categorized them into four tiers: Tier 1 contained the 14 highest group rates.

I created a map showing by state where the highest and lowest backlogs were.  The darker the state color, the higher the backlog.

The IJ charts in the dashboard can be viewed according to whether the IJ worked for DHS or not, showing the percentage of cases denied compared to percentage of cases granted.  The chart can also be filtered by state. I found that IJs with DHS backgrounds showed a definite/no bias toward denials, with the percentage being the same/xxx much different than IJs with no DHS background. I also noted that cases have increased exponentially as current politics seem to dictate a crackdown on illegal immigrants. In addition, to save money on travel and use detention facilities in more locations, the number of hearings conducted by video teleconference has increased by XXX %.  The lack of personal contact makes it easier for an IJ to deny the case.  Therefore, the number of denied cases has increased Therefore, the percentage of backlogged cases has remained the same, even with the increase in IJs.

Although XXXXX typically are below/above the XXXX rate as expected, it became evident that XXXX caused the case denial rate to spike in the years following the 2016 election. The data showed that XXXXXXXXXXXXXXXXXXXXXX, and I discovered that XXXXXXXXXXXXXXXXXXXXXXXXX. If the government added new immigration court locations, the backlog might be even more reduced.  cases held by video teleconference were XXXX % more likely to be denied.  This situation may become more prevalent as a result of COVID-19 protection for court locations and staff.

### Tools Used
• Excel – data was provided as xx separate workbooks

• Python/Pandas - for exploration and aggregation of the data

• Tableau - for creating dashboards
