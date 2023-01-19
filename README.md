# School_District_Analysis
GitHub repository for the analysis of the school data.
# School District Analysis

## Background
Maria, the chief data scientist for a city school district is responsible for analysing information from a variety of sources and in a variety of formats.She is tasked with preparing all standardized test data for analysis, reporting, and presentation to provide insights about performance trends and patterns.

### What are we creating
This assignment consists of five technical analysis deliverables :
-    Collect the student data into a DataFrame.
	Read the data from the new_full_student_data.csv file and store it in dataframe `student_df`.
    
-   Prepare a cleaned version of the DataFrame.
Eliminate the null values , duplicates rows to get a clean data.Verify the datatypes of all the columns and change the datatypes if necessary.

-   Summarize key pieces of the data.
Generate summary statistics for the student DataFrame.Calculate the mean math score of all the students in the district.Also,calculate the minimum reading score in the district.
    
-   Drill down into the data to analyze specific subsets.
Take a look at all the grade levels and then look at the statistical summary of data for grade 9.Look for the row that has the information on minimum redaing score that we calculated before.The school with the lowest reading score is "Dixon High School".Further check the reading score for grade 10 in Dixon High School.Also,calculate the mean of reading score for grade 11 and 12.
    
-   Compare and contrast the data through grouping and aggregation functions.
Calculate the average School Budget for Public and Chartered School.
Take a count of students at each school.Now finally calculate the average math score for each grade in both Public and Chartered schools.

### School Summary

 - Average reading score for all the school is 72.357865 whereas the minimum reading score is 10.500000
 - Average math score for all the school is 64.675733 whereas the minimum math score is 3.700000
 - Upon statistical analysis for Grade 9 data ,we notice the following:-
	 Total no of students is 4132
	  mean reading score is 69.236713 
	  min reading score is 17.900000
	  max reading score is 99.900000
	  mean math score is 66.585624
	  min math score is 5.300000
	  max math score is 100.000000
	  ![image](https://user-images.githubusercontent.com/119648166/213479098-8b01f584-5fbb-4a88-a2e5-c7faf2aeb935.png)

	 
 - The least reading score of 10.5 is from Dixon High School.So we take a  closer look at Grade 10 reading score  for Dixon High School.The average reading score is  67.781898 and max reading score is 99.99.The average reading score for the Grade 11 and Grade 12 is 74.90038089192188
 So ,we see that the average reading score shows an increase as the grade levels go higher.
 - We look at the school budgets at Public School and Charter School.It is seen that Public schools have a little higher budget than Charter schools.
 - Montgomery High School has the highest number of students i.e 2038 and Chang High School has lowest number of students i.e 171.
 - The comparison between mean math score for each grade at Charter school and Public school shows that the Charter schools have higher average math score in most of the Grade levels except Grade 12.
 
 

