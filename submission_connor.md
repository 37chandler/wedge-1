
# Applied Data Analytics

## Wedge Project


### Task 1

* Files for this task: 

**connor_wedge_project_part_one.ipynb**

This notebook: 

1. Unpacks all of the .zip files.
1. Cleans the output.
1. Converts the output into pandas data frames and uploads them to GBQ.



### Task 2

* Files for this task: 

**connor_wedge_project_part_two.ipynb**

This notebook:

1. Queries GBQ to create data frame of all distinct card numbers.
1. Makes a new data frame from 1% sample of those distinct card numbers.
1. Uploads that new data frame back to GBQ.
1. Queries GBQ to get all transaction records for the cards in the sample table.
1. Directly loads query result into local data frame.
1. Writes data frame to a local text file containing transaction results.



### Task 3

* Files for this task: 

**connor_wedge_project_part_two.ipynb**

This notebook:
1. Creates a department lookup table in GBQ to associate department numbers with names
1. Queries GBQ for each of the three requested tables
1. Creates a local database that stores the tables produced by GBQ



## Query Comparison Results

Fill in the following table with the results from the 
queries contained in `gbq_assessment_query.sql`. You only
need to fill in relative difference on the rows where it applies. 
When calculating relative difference, use the formula 
` (your_results - my_results)/my_results)`. 



|  Query  |  Your Results  |  My Results | Difference | Rel. Diff | 
|---|---|---|---|---|
| Total Rows  |85760139|85760139|0|0|
| January 2012 Rows  |1070907|1070907|0|0|
| October 2012 Rows  |1042287|1042287|0|0|
| Month with Fewest  |Feb.|Feb.|No| NA  |
| Num Rows in Month with Fewest  |6556770|6556770|0|0|
| Month with Most  |May|May|No| NA  |
| Num Rows in Month with Most  |7578372|7578372|0|0|
| Null_TS  |7123781|7123792|-11|-1.5440937012206762568922727936305e-5|
| Null_DT  |0|0|0|0|
| Null_Local  |234839|234843|-4|-1.7032655859446523847847285207564e-5|
| Null_CN  |0|0|0|0|
| Num 5 on High Volume Cards  |14987|14987|No| NA  |
|  Num Rows for Number 5 |460630|460625|5|1.0854816824966078697421981004071e-5|
| Num Rows for 18736  |12153|12153|0|0|
| Product with Most Rows  |banana organic|banana organic|No| NA  |
| Num Rows for that Product  |908639|908639|0|0|
| Product with Fourth-Most Rows  |avocado hass organic|avocado hass organic|No| NA  |
| Num Rows for that Product  |456771|456771|0|0|
| Num Single Record Products  |2741|2769|-28|-0.01011195377392560491152040447815|
| Year with Highest Portion of Owner Rows  |2014|2014|No| NA |
| Fraction of Rows from Owners in that Year  |0.7591|0.7591|0|0|
| Year with Lowest Portion of Owner Rows  |2011|2011|No| NA |
| Fraction of Rows from Owners in that Year  |0.7372|0.7372|0|0|

## Reflections

I enjoyed working on this. It was challenging, but you certainly provided plenty of material and support for getting it done. I definitely got better acquainted with some of the related concepts going through this, and got good reps in on more specific technical things as well.
