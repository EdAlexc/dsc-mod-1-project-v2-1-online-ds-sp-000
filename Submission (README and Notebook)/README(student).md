
# Movie genre and title recommendations Readme

## Introduction:
In this Notebook we will be exploring different variables that could affect the success of a movie release. In this exercise we will look at what relationships these variables might have and what hypothetical recommendations would be given to Microsoft for their movie release. 
    

#### The Datasets used for this study 
    1. IMDB
    2. Rotten Tomatoes
    3. TheMovieDB.org
    4. Box Office Mojo





#### The Notebook is divided into the following contents

**A. Exploratory Data Analysis** <br>
  1. Initial exploration and cleanup<br>
      *Data is pulled into DataFrames (df), and each df's columns are examined for primary and secondary keys, unique values, counts of values, nulls and placeholder values that might be representative of nulls.*
  2. Joins<br>
      *DFs are joined and further altered to only include relevant columns and values. Lists within the table df_imdb_title_genre are also expanded for ease of analysis.* 
  
**B. ROI, ratings and production budget(#Rrpb)**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; What is the relationship between ROI, production budget and rating?<br>

*Relationships between ROI, production budget, and ratings are examined and found to not have high correlation. However, there were rating ranges that were associated with typical ROI ranges.*<br><br>

**C. Genres, ROI and rating**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Are there genres that have ratings within our specified range? If so what are their associated ROIs?<br>

*Based on the above ranges genres were studied to see if there were any categories that were indicative of higher ROIs. By some margins the Animation, Adventure and Family genres had the highest ROIs.*<br><br>

**D. Runtime and production budget**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; What is the best range for runtime relative to production budget?<br>
<br>
*Runtimes were examined to see if any relationship existed between it and the other variables already analyzed. It was seen that sticking to less than 120 min would be the best given the aforementioned genres.*
<br><br>

**E. Expected competition**<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Is there a change in the number of released movies from 2015-2019 compared to five years prior?<br>

*Changing industry landscapes were holistically viewed based solely on International ROI and number of movies released for the past decade. It was seen that overall ROI as well as movies released to theatres has decreased over the past 5 years, the same could be attributed in part to the rise of streaming platforms.* <br><br>

**F. Conclusion**<br>

 
