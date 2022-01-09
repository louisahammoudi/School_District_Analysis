# School_District_Analysis
## Overview of the school district analysis: 
This project analyses  Data from  diffrents sources from city school district,Our analysis consists on preparing (cleaning ),reporting and presenting the data , this data will form inputs to discussions and strategic decisions at the school and district level about the school budget and priorities and students standardized test scores.

Further to our analysis, we are investigating the evidence of academic dishonesty  reported in the  students_complete.csv file provided ;
 reading and math scores for Thomas High School ninth-graders looks like been altered.  the school board want to uphold state-testing standards. 
 our analysis will replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. We would then repeat the school district analysis and show how the changes affected the overall analysis.

After replacing 9th grade math and reading scores for Thomas High School with NaN, the results of our analysis changed the following results:
District Summary: % Passing Math, % Passing Reading, and % Overall Passing  drooped .
District Summary including 9th Grade Thomas High School
![image](https://user-images.githubusercontent.com/93894919/148669030-f5248031-7fc2-4966-9ec2-5d319b12ee39.png)
District Summary excluding 9th Grade Thomas High School
<img width="629" alt="Capture1" src="https://user-images.githubusercontent.com/93894919/148669164-09c24ec7-cf9b-4f0c-8102-491480df8aff.PNG">

The overall passing percentage for Thomas High School fell to 65%
The overall passing percentage for the entire district fell to 64.9%
Thomas High School was no longer included on the list of top five schools.
When the ninth graders' of Thomas High School had their scores omitted from the calculations, the following changes occured:

The overall passing percentages of Thomas High School decreased by 0.11%
The average scores of Thomas High School for math and reading increased by 0.06
For the spending range of $630-644 per student, the overall passing percentage decreased by 0.1%
School rankings are unchanged. Thomas High School is still the second best performing school in the district with an overall passing rate of 90.63% among their tenth through twelfth graders.
The Effects of School Budget and School Size
It is found that Average Scores and Passing Percentages do not increase as spending per student increases. In fact, the top performing school in the entire school district (Cabera High School) received $68 less per student than the lowest performing school (Johnson High School). This implies that there are more relevant factors than funding that decide average student scores.


## Summary
Unfortunately, it is not possible to determine the extent of the potential academic dishonesty or identify soecific indivuals to exclude from the dataset. As a consequence of this, the entire ninth grade of students from Thomas High School have had their scores omitted from the results. This is a suboptimal situation because a full set of data is ideal for creating the most accurate results.

Relacing the ninth graders' scores with NaN caused Thomas High School's overall passing percentages and average scores to plummet. The district as a whole has also had its average math and reading scores decrease, as well as the overall passing percentage for students. Furthermore, Thomas High School lost its placement as a top five school within this District. However, after updating the total student counts to exclude the Thomas High School ninth graders and omitting their scores from the dataset, Thomas High School regained its high average scores and retained its position as the number two school in the District. 
