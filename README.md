# School_District_Analysis

## Overview of Project

### Purpose
A school board consultant has asked for my assistance in analyzing some academic data and produce metrics to understand how their
students are performing in class as well as how certain budgets may impact student performance.  The required school board metrics 
are identifed below. The consultant delivered a CSV file to perform the analysis.  The analysis was completed and delivered to the
school board; however, they have recently informed us that the CSV file shows evidence of academic dishonestly.  The dishonesty 
points specifically to ninth graders "reading and math" grades from Thomas High School. 

The consultant has asked me to replace these "reading and math" grades with "NaN" while keeping the rest of the data intact.  
I will also need to repeat the district analysis before turning in my final analsys report.  The standard data analysis principles 
were used which includes; (1) Determine the number of rows and columns; (2) Data types used; and (3) Is the data readable?

School Board Required Metrics:

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average reading score for each grade level from each school
- The scores by school spending per student, by school size, and by school type

## Resources
School Data source: [School Data](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/schools_complete.csv)

Student Data source: [Raw Students Data](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/students_complete.csv)



## Results

The below bullets will describe the school analysis results.
  
  - How is the district summary affected?
  	- The district summary does not appear to have been impacted much based on the results captured below.
	
	Pre grades replacement: ![District Summary Pre grade replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/DistrictSummary_PreDishonestDiscovery.PNG)

	Post grades replacement: ![District Summary Post grades replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/DistrictSummary_PostDishonestDiscovery.PNG)

  - How is the school summary affected?
	- The school summary for Thomas High School was impacted.  Prior to the dishonest discovery, Thomas High School passing percentages
	  in reading and math were over 90%.  Once the Thomas High School 9th grade data was omitted, their passing percentages for math, reading
	  and overall passing percentages were below 70% based on the below results.

	Pre grades replacement: ![School Summary Pre grades replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/SchoolSummary_PreDishonestDiscovery.PNG)

	Post grades replacement: ![School Summary Post grades replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/SchoolSummary_PostDishonestDiscovery.PNG)

  - How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
	- The below images illustrate the affect of replacing the ninth graders' math and reading scores for Thomas High School.

	Pre grades replacement: [Replacing Ninth graders pre grades replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ReplacingNinthGraders_PreDishonestDiscovery.PNG)

	Post grades replacement: [Replacing Ninth graders data post grades replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ReplacingNinthGraders_PostDishonestDiscovery.PNG)

  - How does replacing the ninth-grade scores affect the following:
  
  	- Math and reading scores by grade
		- Even after this data was replaced the math and reading scores were still slightly over a 'B'.  The below images will illustrate this.
		
		Pre grades replacement: [Replacing Ninth graders pre grades replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ReplacingNinthGraders_PreDishonestDiscovery.PNG)

		Post grades replacement: [Replacing Ninth graders data post grades replacement](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ReplacingNinthGraders_PostDishonestDiscovery.PNG)

	- Scores by school spending
		- The below images will illustrate the scores by school spending per student.

		Pre grades replacement: [Replacing Ninth graders data Pre Discovery](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ScoresbySchoolPerStudent_PreDishonestDiscovery.PNG)

		Post grades replacement: [Replacing Ninth graders data Post Dishonest Discovery](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ScoresbySchoolPerStudent_PostDishonestDiscovery.PNG)


	- Scores by school size
		- The below images will illustrate the scores by school size.

		Pre grades replacement: [Replacing Ninth graders data Pre Discovery](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ScoresbySchoolsize_PreDishonestDiscovery.PNG)

		Post grades replacement: [Replacing Ninth graders data Post Dishonest Discovery](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ScoresbySchoolsize_PostDishonestDiscovery.PNG


	- Scores by school type
		- The below images will illustrate the scores by school type.

		Pre grades replacement: [Replacing Ninth graders data Pre Discovery](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ScoresbySchoolType_PreDishonestDiscovery.PNG)

		Pre grades replacement: [Replacing Ninth graders data Pre Discovery](https://github.com/SheaButta/School_District_Analysis/blob/main/Resources/ScoresbySchoolType_PostDishonestDiscovery.PNG)

## Summary

The school district analysis revealed some data changes that occurred after replacing the ninth graders' data for Thomas High School.
The specific changes that were revealed are as follows;

	1. The "% Passing Math" was altered because of this replacement.  The "% Passing Math" was originally "93.3%" and 
	   after the data replacement it was "66.9%".

	2. The "% Passing Reading" was altered because of this replacement.  The "% Passing Reading" was originally "97.3%" and 
	   after the data replacement it was "69.7%".

	3. The "% Overall Passing" was altered because of this replacement.  The "% Overall Passing" was originally "99.9%" and 
	   after the data replacement it was "65.1%".

	4. The ninth graders of Thomas High School had a math score by grade of 83.6 prior to the replace.  There is no math 
	   score by grade for the ninth graders of Thomas High School.

	5. The ninth graders of Thomas High School had a reading score by grade of 83.7 prior to the replace.  There is no reading 
	   score by grade for the ninth graders of Thomas High School.

