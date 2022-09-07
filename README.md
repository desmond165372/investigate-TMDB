# Investigate-TMDB
# By Chiedozie Desmond
## Dataset
The Movie Database(TMDb) is a cleaned data collected from [Udemy](https://www.google.com/url?q=https://d17h27t6h515a5.cloudfront.net/topher/2017/October/59dd1c4c_tmdb-movies/tmdb-movies.csv&sa=D&ust=1532469042115000). This data set contains  information of about 10,000 movies. <br>
 ##### The data set has: 10866 movies and 21 features 

### some of the analysis carried out are: 
1. The year that has the highest revenue
2. the year that has the highest released movies
3. the year that has the highest profit
4. The movie with the highest profit
5. Theh movie with the highest revenue
6. The production company with the highest revenue
7. How the average runtime affect vote ratings 

## Key Insight for Presentation
First, some data wrangling was done and the following observations were noted:
#### Observations
1. There are 10866 movies and 21 columns.
2. there are some missing data in the 'home page', 'cast', 'director', 'tagline', 'production_companies', 'keywords'.
3. one duplicated value count which will affect the analysis and need to be droppede.
4. There are some colums which are not needed in my analysis that also needs to be dropped.
5. The release_date column is in object data type and should be changed to date time format.
6. There are 13434 missing values in total and should be fill with 0.

In addition, explorartory data analysis(EDA) was performed using different plots e.g bar plot, line plot, histogram, pie chart and some mind blowing insights was made.

## Summary of Findings
In the exploratiion, some insights was drwan and the following recommendations were made:
1. Avatar generated the highest profit so the producer company should consider producing Avatar2.
2. Year 2009 has generated the highest profit so far, therefore the tecnquines or tools used in 2009    should be considered if the producer companies want to generate such profit again.
3. Producer companies should produce more of Comedy genre if they want to generate more profit.
4. Producer should produce more of Drama|Horror|Mystery|Science Fiction|Thriller if they desire to      get more vote ratings.
5. To get more vote ratings, movies with average runtime greater than 102mins should be produced        more.
