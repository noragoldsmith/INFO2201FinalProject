# INFO2201FinalProject

Notes on Data Source

Where are you getting it from?
2024 Annual Report from AmericasHealthRankings.org (United Health Foundation)
This is data source that includes statistics about health from multiple surveys and organizations 
What data type is it?
The data is a cvs file
What are the restrictions of that data type (Gaps? Ethics?)
Pros and cons of this data source in terms of accessibility

Walk Through of Data Pulling
Where did you get it from?___________
U.S. Department of Health and Human Services, 2022-2023
Centers for Disease Control and Prevention, 2023
Behavioral Risk Factor Surveillance System, 2023
Health Resources and Services Administration, 2022-2023
Maternal and Child Health Bureau, 2022-2023
National Survey of Children’s Health, 2022-2023
U.S. Census Bureau, 2023
American Community Survey, 1-Year Dataset, 2023
U.S. Department of Agriculture, 2023
Economic Research Service, 2023
Household Food Security in the United States Report Series, 2021-2023
How did you get it?
Iterated through rows of the csv file of data from all surveys and organized information into a dictionary

Walk Through of Data Cleaning_______________

- What choices did you make?
- --> When cleaning our data, we first isolated our variables of focus from the csv file, which were Depression and Depression-Other Variable statistics from the original data file
- --> In addition, we selected and isolated other variables that we thought could help explain and give context to certain depression trends across states 
- --> After reviewing the ranking of each state's depression statistics, we decided to select 5 states that illustrated the differing levels of depression thorughout the country. (We chose the state with the highest level of depression, lowest level of depression, the middle level of depression, and the first quartile level of depression and 3rd quartile level of depression)
- --> After choosing our 5 states, we looked at the data on depression and how different factors such as age, gender, income level etc were at play
- --> Our hope to explore if such factors could provide insight onto the depression rankings, and compare such factors in each state
We wanted to explore possible explanations for the prevalence of depression in certain states (eg. statistics of states with a high depression score vs low depression score)

- What was selected/deleted?
- --> We only selected the columns from our data that matched our desired variables. The original survey included variables such as survey name, date, index number, and upper and lower cis, that was not relevant information for our analysis. Thus, we deleted those columns.
- --> We only extracted data from the "CDC, Behavioral Risk Factor Surveillance System Survey", and all of the responses were from the 2024 annual report which included survey responses from 2023.


- Why?
- --> When making our tables, we deleted certains columns to avoid unnecessary cleaning/deleting of data, as well as make the visuals easier to understand.

Reflection on Visualizations________________

Implications for visualization
possible other visualizations in readme

Storytelling/Insight
Where is this helpful?
What should other people draw conclusions about from your visualizations and cleaning?

