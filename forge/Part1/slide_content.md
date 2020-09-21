### Title: Descriptive title of your project

# CrimeIntel
# A data-mining oriented approach to public safety

### Team members: first and last name of each member
Aaron Shyuu | Max Smith | Thomas Dolan


### Description: 2-3 sentence paragraph project description - what interesting questions do you intend to answer?
#### TO-DO:
[ ] Consolidate these:

THOMAS
Is crime paired with Holiday weekends? Is crime seasonal?
What are the top 5 deadliest settings (time/place) (can we map?)
how is crime related to economic boom and bust?

MAX
Do violent & non-violent crime differ geographically?
Are V & NV crime trends correlated? 
What trends exist? Total? By crime type?
Do trends persist from year to year / by location?
Are crime types categorically clustered?


AARON
Is there a correlation between crime and time of year and location?
Classification - Predict crime type based on month/time of crime and location.
Classification / outlier analysis - What are dangerous and safe neighborhoods based on patterns of crime? (Crime distribution in Chicago for ex.)
Predict how much crime in the future in Chicago (based on some attributes)



### Prior Work: What prior work has been done on your idea

#### TO-DO:
[ ] Update slides, slide3 in particular, when Datasets and Proposed Work are laid in stone. 

[slide1]
Chicago Crime Data set is a publicly accessible data set on Google’s Big Query. 
Quite a few people have used this dataset in their own analyses on Chicago Crime and for learning how to use Big Query, some of which have yielded unique and interesting results.
Crime in Chicago has also been the focus of many government and academic studies and initiatives as well. 


[slide2]
Some interesting examples:
https://www.kaggle.com/mkrkkinen/chicago-crime-on-christmas
https://www.kaggle.com/alkadri/chicago-codes-crime-map-and-bigquery-in-r
https://medium.com/@stafa002/my-notes-on-chicago-crime-data-analysis-ed66915dbb20
https://cjango.wordpress.com/portfolio/chicago-crime-data-analysis-python-project/
https://www.ipr.northwestern.edu/news/2018/crime-in-chicago-research.html
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3831577/


[slide3]
In order to yield a novel analysis, we will be taking several steps in our data mining process that we have not seen used elsewhere. 
Differentiating violent from non-violent crime, per http://gis.chicagopolice.org/clearmap_crime_sums/crime_types.html
Using Chicago’s Community Areas to join crime date with other datasets and to identify other unique trends and relationships. https://en.wikipedia.org/wiki/Community_areas_in_Chicago


### Datasets:
- List of datasets to use
- Where found (URL and who is supplying the data, e.g., NASA)
- Whether it you have it downloaded (on who’s machine)

https://www.kaggle.com/chicago/chicago-crime
https://data.cityofchicago.org/Public-Safety/Boundaries-Police-Beats-current-/aerh-rz74


### Proposed work: what do you need to do?

#### TODO:
[ ] Finalize Datasets and questions so this can be completed. 

[slide1]
Data cleaning:
 - handling of Null Values

[slide2]
Data preprocessing:
 - converting nominal attributes, in particular 'primary type', 'description', and 'location description' into numeric codes. 
 - converting arrest and domestic attributes into boolean values
 - grouping data by date hierarchy for matching financial data? 

[slide3]
Data integration:
 - create new boolean attribute identifying crime as violent or non-violent by joining crime transactions 'primary type' (or FBI code?) to data in  
 - integrate economic data using ??? 



### List of tool(s) you intend to use
- Google Big Query
- Jupyter Notebooks
- SQL
- Python
- Pandas / Numpy
- Tableau
- D3.js

### Evaluation: How you can evaluate your results
