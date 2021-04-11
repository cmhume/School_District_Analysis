

# School District Analysis


## Overview


The purpose of this analysis was to redo a previously completed school district analysis, removing student scores that appeared to be altered.  All of the ninth grade math and reading scores for Thomas High School shown in the students_complete.csv file were replaced with NaNs and the school district analysis was run again using only the math and reading scores for tenth through twelth graders for Thomas High School.  The results were compared with the original school district analysis that included Thomas High School's ninth grade scores to note the impact of the possibly altered scores on Thomas High School's performance.  In both analyses, the data from the schools_complets.csv and students_complete.csv were merged into one dataframe in jupyter notebook to show the name of the school, the school type, total number of students, the total school budget, the average math score, the average reading score, the percent passing math, the percent passing reading, and the percent of overall passing.  Fifteen schools and a total of 39,170 students (before removing Thomas High School's ninth grade scores) were included in the analysis.  From this data frame, other dataframes and analyses were performed including, the district summary, the school summary, top five performing schools, bottom five performing schools, average math score by grade level for each school, average reading score by grade level for each school, scores by school spending per student, scores by school size, and scores by school type.  Jupyter Notebook in Anaconda's "PythonData" environment was used to perform the updated school district analysis using the blue print from the original school district.  The Pandas library and python language were also used in this analysis.


## Resources


PythonData environment in Anaconda including:


Python version 3.7.9


Anaconda version 2020.11


Pandas version 1.1.3


Jupyter version 1.0.0

files:

schools_complete.csv


https://github.com/cmhume/School_District_Analysis/blob/2104416856496593c54301b0984e7869729d3f8a/Resources/schools_complete.csv


students_complete.csv


https://github.com/cmhume/School_District_Analysis/blob/2104416856496593c54301b0984e7869729d3f8a/Resources/students_complete.csv



## Results



The results for the updated school district analysis are available here: https://github.com/cmhume/School_District_Analysis/blob/2104416856496593c54301b0984e7869729d3f8a/PyCitySchools_Challenge.ipynb  


The results from the original school district analysis are available here: https://github.com/cmhume/School_District_Analysis/blob/2104416856496593c54301b0984e7869729d3f8a/PyCitySchools.ipynb


* ### District Summary


  The updated district summary had a lower average math score (78.9 compared to 79), a lower % passing math (74.8%, compared to 75%), a lower % passing reading (85.7%, compared   to 86%) and a lower overall passing %(64.9%, compared to 65%) when compared with the original district summary.
  
  
* ### Thomas High School Summary 


  The updated school summary for Thomas High School had a higher average reading score compared with the original school summary (83.9 compared to 83.8).  The other values were   the same compared with the original school summary. 
  
  
* ### Thomas High School's performance compared with other schools


  Replacing the ninth graders' math and reading scores increased Thomas High School's overall performance, moving Thomas High School up from fourth top school to second top
  school. 
  
  
* ### The affect of replacing Thomas High School's ninth-grade scores with "nan" on:


  *  #### math and reading scores by grade
  
  
      Replacing the ninth-grade scores for Thomas High School with "nan" left the updated math_scores_by_grade and reading_scores_by_grade dataframes with "nan" in the 9th grade
      column.
      
      
  *  #### Scores by school spending
  
  
      Replacing ninth-grade math and reading scores for Thomas High School with "nan" had no affect on the updated spending summary when compared with the original spending
      summary.
    
  
  *  #### Scores by school size
  
  
      Replacing ninth-grade math and reading scores for Thomas High School with "nan" had no affect on the updated scores by school size dataframe when compared with the
      original scores by school size dataframe.
   
   
  *  #### Scores by school type
  
  
      Replacing ninth-grade math and reading scores for Thomas High School with "nan" had no affect on the updated scores by school type dataframe when compared with the
      original scores by school type dataframe.
    
    
### Comparison of updated school district analysis results with original school district analysis results


#### Removing ninth grade math and reading scores from Thomas High School for updated school district analysis:


![replacing_9th_grade_scores](https://user-images.githubusercontent.com/78699521/114321116-f7206280-9acd-11eb-8e43-5c45c1adb2e0.png)


#### District summary-


##### Updated district summary, without ninth grade reading and math scores:
  

![new_district_summary](https://user-images.githubusercontent.com/78699521/114277299-784cfc00-99df-11eb-9046-1a33691ce600.png)


##### Original district summary with ninth grade reading and math scores:


![original_district_summary](https://user-images.githubusercontent.com/78699521/114277294-7125ee00-99df-11eb-8069-d01421bc6b34.png)


#### Thomas High School summary-


##### Updated school summary:
  
  
![updated_school_summary](https://user-images.githubusercontent.com/78699521/114321864-01446000-9ad2-11eb-9a63-99308480c24d.png)

    
##### Original school summary:
  
  
![original_school_summary](https://user-images.githubusercontent.com/78699521/114278267-c9f78580-99e3-11eb-983f-974f4b5ede36.png)


#### Top five schools-


##### Updated top five schools:
  

![updated_top_schools](https://user-images.githubusercontent.com/78699521/114321867-09040480-9ad2-11eb-9ea1-ab780716c5ea.png)

  
##### Original top five schools:
  
![original_top_schools](https://user-images.githubusercontent.com/78699521/114278577-58b8d200-99e5-11eb-8976-90745bedd536.png)
      
      
#### Math and reading scores by grade-


##### Updated math and reading scores by grade:
     

![updated_math_scores_by_grade](https://user-images.githubusercontent.com/78699521/114279351-0974a080-99e9-11eb-83ec-2d9b568e9e10.png) ![updated_reading_scores_by_grade](https://user-images.githubusercontent.com/78699521/114279354-0ed1eb00-99e9-11eb-940b-508fdcbd0b81.png)
     
     
##### Original math and reading scores by grade:
    
     
![original_math_scores_by_grade](https://user-images.githubusercontent.com/78699521/114279374-2c06b980-99e9-11eb-8380-384f385ec8be.png) ![original_reading_scores_by_grade](https://user-images.githubusercontent.com/78699521/114279377-2f9a4080-99e9-11eb-8ce2-be6618065d58.png)


#### Spending Summary-


##### Updated Spending Summary:


![updated_spending_summary](https://user-images.githubusercontent.com/78699521/114279531-03cb8a80-99ea-11eb-9cc3-5f4bb0c58387.png)
     
     
##### Original Spending Summary:
     
     
![original_spending_summary](https://user-images.githubusercontent.com/78699521/114279533-0b8b2f00-99ea-11eb-9a64-540cbe5e6fba.png)


#### Scores by school size-


##### Updated scores by school size:
  
  
![updated_scores_by_size](https://user-images.githubusercontent.com/78699521/114279830-6a04dd00-99eb-11eb-9fcc-ddf21f195bd6.png)
  
  
##### Original scores by school size:
  
  
![original_scores_by_size](https://user-images.githubusercontent.com/78699521/114279846-76893580-99eb-11eb-903b-ffef5d31bf51.png)


#### Scores by school type-


##### Updated scores by school type:


![updated_scores_by_type](https://user-images.githubusercontent.com/78699521/114279870-97518b00-99eb-11eb-999c-9e512d5d4551.png)


##### Original scores by school type:
  
  
![original_scores_by_type](https://user-images.githubusercontent.com/78699521/114279896-b05a3c00-99eb-11eb-9a29-86d712128985.png)


## Summary


Removing the ninth grade scores from Thomas High School improved it's overall standing, moving the highshool up from fourth top school to second top school in the district.  The district summary had slightly lower values in average math score (78.9 compared to 79), % passing math(74.8%, compared to 75%), % passing reading (85.7% compared to 86%) and % overall passing (64.9% compared to 65%).  The average reading score in the district summary was the same in both analyses. In the per school summary dataframe, Thomas High School had a higher average reading score compared with the original analysis, while the other values remained the same.  This improvement raised Thomas High School's overall standing to second in the district.  The ninth grade scores by grade were not available for Thomas High School because they were replaced by NaNs at the beginning of the analysis.  This action prevented the analysis of ninth grade scores for Thomas High School.  The district spending summary, scores by school spending, score by school size and scores by school type were unchanged in the updated analysis compared with the original analysis.  Overall, the changes in the updated analysis compared to the original analysis  ranged from .1% to .3% different in the percent passing scores and a difference of  0.1 units from the original's average math score.  The changes were significant enough to change Thomas High School's standing in the district and lower some of the values in the district summary, but were not significant enough to change the average reading score, spending summary, scores by school size, or scores by school type.    





