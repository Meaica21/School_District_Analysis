# School_District_Analysis

## Overview of school district analysis:
 The purpose of this analysis was to clean and show the effect of removing the academic dishonesty in Thomas High School’s reporting of 9th grade math and reading scores.  Once the data was organized, passing grades for math and reading were updated with the new computation for Thomas High School.
 
 ## Results: 
  1. How is the district summary affected?
      -	The district summary data frame columns, such as % Passing Math, % Passing Reading, % Overall Passing, increased after removing the Thomas High School’s 9th grade Math   and Reading scores as shown in Figure 1. This means that Thomas High School’s 9th grade Math and Reading scores were below the average of all the other schools.
      
      ![Figure 1](https://user-images.githubusercontent.com/83877498/121821796-53883580-cc69-11eb-871e-f6a62289194a.PNG)
      
      * Figure 1:  Calculation of percentage of Passing Math and Reading and Overall Passing 
      
      ![Figure 2](https://user-images.githubusercontent.com/83877498/121821841-9d711b80-cc69-11eb-9637-46413a68c4e7.PNG)

      * Figure 2:  Difference of total percentage for % Passing Math, % Passing Reading and % Overall Passing columns after removing the nine graders from Thomas High School 

  2. How is the school summary affected?
    - -	Thomas’s High School’s total percentage for % Passing Math, % Passing Reading and % Overall Passing columns were increased for all students from 10th-12th grader with passing score of 70 and above.
      ![Figure 3](https://user-images.githubusercontent.com/83877498/121821852-b2e64580-cc69-11eb-9cb5-094b2e454758.PNG)
      
      * Figure 3: Original value of Thomas High School for all students

      ![Figure 4](https://user-images.githubusercontent.com/83877498/121821864-c5607f00-cc69-11eb-8586-432daab42f31.PNG)
      
      * Figure 4: Updated per_school_summary_df for Thomas High School

  3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    - Thomas High school became 2nd top school based on the % Overall Passing by replacing math and reading scores of the ninth graders.
     
   ![Figure 5](https://user-images.githubusercontent.com/83877498/121821894-efb23c80-cc69-11eb-9f54-059cdd2014c4.png)
    
   * Figure 5: High and Low Performing Schools

  4. How does replacing the ninth-grade scores affect the following:
      1.	Math and reading scores by grade
      - For Thomas High School, 9th grade scores were affected in that they were replaced with NAN.  The other grades remain unaffected.
      
      ![Figure 6](https://user-images.githubusercontent.com/83877498/121821951-491a6b80-cc6a-11eb-81c5-8b6c9e599510.PNG)

      * Figure 6: Math and reading scores by grade
      2.	Scores by school spending
       - It increased the average of the lowest spending tier. 
       
       ![Figure 7](https://user-images.githubusercontent.com/83877498/121821964-6818fd80-cc6a-11eb-95ab-ea6a539353bc.PNG)
       
       * Figure 7: Scores by school spending
       
      3.	Scores by school size
        - It raised the average and percentage of the Medium sized schools.		
        
        ![Figure 8](https://user-images.githubusercontent.com/83877498/121821992-8da60700-cc6a-11eb-9e3d-e17097880a64.PNG)
        
        * Figure 8: Scores by school size

      4.	Scores by school type
       -  Charter type schools average and percentage increased, and District remained unchanged.
        
       ![Figure 9](https://user-images.githubusercontent.com/83877498/121822009-a8787b80-cc6a-11eb-962d-87411c4cde04.PNG)

        * Figure 9: Scores by school type
        
   ## Summary: 
   In this activity, it evidently shows the percentage of Passing Math, Passing Reading and Overall Passing columns improved by replacing the math 
 and reading scores to a NAN value for nine graders for Thomas High School.
   It changes the average of Thomas High School for math and reading scores. Thomas High School became 2nd top performing school. 
   It also increased the average of the lowest spending tier school while raising average and percentage of charter type school.
