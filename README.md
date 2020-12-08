# CrimeIntel
## A Data Mining Oriented Approach to Public Safety
#### Aaron Shyuu | Max Smith | Thomas Dolan

### Project Submissions:
[PART 1 SUBMISSION](04_CrimeIntel_Part1.pdf)<br>
[PART 2 SUBMISSION](04_CrimeIntel_Part2.pdf)<br>
[PART 3 SUBMISSION](04_CrimeIntel_Part3.pdf)<br>
[PART 4 SUBMISSION](04_CrimeIntel_Part4.pdf)<br>
[PART 6 SUBMISSION](04_CrimeIntel_Part6.pdf)<br>

### Description of the project
Our project employs data mining methods on the Chicago Crime public dataset, hosted by Google as part of their BigQuery project, with the goal of yielding interesting information relating to the cause, prediction, and general topography of crime in Chicago. In doing so we hope to add an unbiased and data-driven voice to the analysis of crime in Chicago. 

### Summary of the question(s) sought and the answers

Major Questions:<br>
•	Crime has steadily decreased since 2002, but plateaued in 2016. Why might crime have plateaued? <br>
•	Is there a correlation between crime in Chicago and various economic indicators? <br>
•	What can we learn about where and when specific kinds of crime are happening by analyzing assocations between crime type categorizations and their location and time data? Does adding more crime categorization information reveal any additional insights to these results? <br>
•	Using classification methods, can we predict whether an arrest will be made? <br>


Answers:<br>
• Using linear regression, we found that three crimes accounted for 70% of the plateau- theft, battery, and narcotics. During the decline years, one could expect these crimes to drop by approximately 6,000, 5,000, and 4,000 instances per year (respectively).  These dropoffs evaporated in 2016, leading to the plateau.	 <br>
• We did not find a relationship between economic indicators and crime in Chicago, however, using outlier analysis, we were able to uncover an interesting pattern.  We used global outlier techniques for our economic data and contextual outlier analysis for our crime data.  We did not find any outliers in our crime data, but we did find an outlier in our economic data in April 2020.  We then inspected the crime data during that period and found an extended period (April 2020-July 2020) of unusually low crime.  We attributed this to COVID-19 due to the nature of the crime during this time period (higher domestic crime relative to total crime). <br>
•	We found three major crime hotspots through frequent itemset mining, confirming our initial exploratory data analysis findings. We learned key insights into the types and locations of crime occuring in those areas, as well as a few major time indicators for certain kinds of crime in those. We gained several entry points for additional analysis based on these results. We also gained several additional insights using new categorization attributes, verifying the usefulness of additional categorization types in the process. These specific findings can be found in the Question 3 - Frequent Mining notebook enclosed in this project.  <br>
•	 <br>

### Application of this knowledge
• It is desirable for both public servants and residents of Chicago to get back to pre-2016 crime trends.  One strategy would be to allocate additional resources to law enforcement specifically to combat the top three drivers of the plateau- theft, narcotics, and battery. <br>
• The drop in crime between April 2020 and July 2020 is correlated with the COVID-19 restrictions.  We can also say that, due to the makeup of crime during this period, the reduction in crime is likely caused by COVID-19 restrictions. If this is true, the reduction in crime is likely temporary and therefore no major policy decisions regarding law enforcement should be made based on this trend.	 <br>
•	With our frequent itemset mining results, organizations looking to curb crime or enact positive change in the community can gain insights on how best to allocate their resources. Sidewalk crime tied to drug abuse in the Austin community area, particularly along West Ferdinand St, as well as the surrounding communities of West Garfield, Humboldt, and North Lawndale, indicates a strong need for public services addressing homelessness and addiction, as well as the curtailing of gang activities. The high rate of larceny in The Loop shows the everpresence of retail theft wherever department stores and grocery stores are central, which could be assisted in the knowledge that most retail theft occurs between noon and 5pm. The high association between crimes such as pickpocketing and credit card fraud as well as the increased association with crime occuring in bars, restaurants, and hotels in the Near North Side show the usefulness something like an ad compaign targeted at tourists might have. Generally speaking, the weekends are most dangerous. Finally, entities like community organizers and child protective services in addition to law enforcement should be aware of the high association between crime and apartments in the South Chicago and Avalon areas, specifically on the blocks of E 68th St, E 70th St, E 78th St, E 80th St, E 81st St, E 82nd St, and S South Shore Dr.  <br>
•	 <br>



### Video Demonstration
[Link to brief Video Presentation]()


### Final Project Paper
[Link to Final Project Paper](04_CrimeIntel_Part4.pdf)

