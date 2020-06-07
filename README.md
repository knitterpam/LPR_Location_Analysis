# Legal Permanent Resident (LPR) Location Analysis

## Analysis of Concentrations of Legal Permanent Residents (LPR) by Country and Class of Admission
### Motivation
Since 2013 I have transcribed immgration hearings for a company contracted to the Department of Justice (DOJ).  I primarily transcribe hearings for illegal immigrants, but I wanted to know more about where legal permanent residents (hereafter "LPR") tend to settle and the migration changes over the past decade.  I plan to explore the following:

 Where are the top 10 largest concentrations of LPRs over the data available by A) country of birth and B) class of admission (grouped, as there are a number of subgroups within each type)?
 How have these concentrations changed over time (data available for period 2007-2018)?

### Data
To answer these questions, I used immigration data provided by the Department of Homeland Security over the years 2007-2018.  I hope to be able to map current county of residence using geolocation data, if available.  I may bring in some UN GDP data to add further comparisons.

### Analytical Approach
Known Issues and Challenges:
 There are many redacted fields in the datasets where the government withheld the data on how many LPRs were admitted.  I plan to convert these to 1, rather than deleting or using 0.  Fully deleting these rows might better represent the diversity in the data.
 The LPR tables are limited to top 200 counties by size of admission. Only state and county are listed (not city) for current LPR location.  I'll need to explore this to see if cities need to be added in for accuracy or visualization.

I created a map showing by state/city/county where the top 10 concentrations of LPRs are located by year.  Bubble size indicates size of concentration.

I used bar charts to show the top 10 countries of birth for LPRs by year to look at the changes in where LPRs are coming from.  These may correlate to world events and may show a trend in certain areas.

### Tools Used
• Excel – LPR data was provided as 11 separate workbooks, with XXXXXXXXXXXXXX added to provide further analysis.

• Python/Pandas - for exploration and aggregation of the data

• Tableau - for creating dashboards
