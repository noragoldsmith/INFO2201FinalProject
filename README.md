# INFO2201FinalProject

## Notes on Data Source
### Where are you getting it from?
- 2024 Annual Report from AmericasHealthRankings.org (United Health Foundation)
- This is data source that includes statistics about health from multiple surveys and organizations 

### What data type is it?
- The data is a csv file

### What are the restrictions of that data type (Gaps? Ethics?)
- Although the csv file contained a large amount of data, some of the cells were missing values so we were unable to use certain variables for our visualizations.

### Pros and cons of this data source in terms of accessibility __________________
- Pros:
  - Contained a large amount of data to view and consider
  - Organized by variable, which made the file easy to navigate for our purposes
- Cons:
  - Did not provide a lot of context as to what certain values meant or how the data was collected, however that information was available on a separate site

## Walk Through of Data Pulling
### Where did you get it from?
- U.S. Department of Health and Human Services, 2022-2023
- Centers for Disease Control and Prevention, 2023
- Behavioral Risk Factor Surveillance System, 2023
- Health Resources and Services Administration, 2022-2023
- Maternal and Child Health Bureau, 2022-2023
- National Survey of Children’s Health, 2022-2023
- U.S. Census Bureau, 2023
- American Community Survey, 1-Year Dataset, 2023
- U.S. Department of Agriculture, 2023
- Economic Research Service, 2023
- Household Food Security in the United States Report Series, 2021-2023

### How did you get it?
- Iterated through rows of the csv file of data from all surveys and organized information into a dictionary

## Walk Through of Data Cleaning
### What choices did you make?
- When cleaning our data, we first isolated our variables of focus from the csv file, which were Depression and Depression-Other Variable statistics from the original data file
- In addition, we selected and isolated other variables that we thought could help explain and give context to certain depression trends across states 
- After reviewing the ranking of each state's depression statistics, we decided to select 5 states that illustrated the differing levels of depression thorughout the country. (We chose the state with the highest level of depression, lowest level of depression, the middle level of depression, and the first quartile level of depression and 3rd quartile level of depression)
- After choosing our 5 states, we looked at the data on depression and how different factors such as age, gender, income level etc were at play
- Our hope to explore if such factors could provide insight onto the depression rankings, and compare such factors in each state
- We wanted to explore possible explanations for the prevalence of depression in certain states (eg. statistics of states with a high depression score vs low depression score)

### What was selected/deleted?
- We only selected the columns from our data that matched our desired variables. The original survey included variables such as survey name, date, index number, and upper and lower cis, that was not relevant information for our analysis. Thus, we deleted those columns.
- For our visualizations of depression demographics, we only extracted data from the "CDC, Behavioral Risk Factor Surveillance System Survey". The rest of the data are from other various surveys from the 2024 annual report listed in the "Where did you get it from?" section of this ReadMe, which included survey responses from 2022, 2023, and 2024.

### Why?
- When making our tables, we deleted certain columns to avoid unnecessary cleaning/deleting of data, as well as make the visuals easier to understand. For example, we weren't interested in the columns labeled "Lower Cl" and "Upper Cl", so we omitted them from our final dataframes.

## Reflection on Visualizations
### Implications for visualizations
- When analyzing the prevalence of depression across our chosen factors, many times the factors contributed to rates of depression higher than the national average, which highlights the importance of targeted approaches when dealing with mental health
- Understanding how depression manifests itself in various ways is important for creating and proposing informed solutions such as new policies, improved resources, or further research
- Our visualizations serve as evidence to continue the research and development of mental health treatment geared towards vulnerable communities, such as low income Americans and those living below the poverty line


## Storytelling/Insight
### Where is this helpful? ______________________

### What should other people draw conclusions about from your visualizations and cleaning? ________________

