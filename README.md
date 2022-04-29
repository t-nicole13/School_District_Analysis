# School_District_Analysis

## Overview 
For this project, I used Python and Pandas to analyze school district data.  There was an issue with academic dishonesty involving Thomas High School. So, I decided to do an analysis with and without Thomas High School's data to see how much of a change there would be between the original and updated analysis.

Pandas is a great tool to use for analyzing and manipulating data.  It is built on top of the Python programming language.  For the second analysis, I used the Pandas Numpy method to change Thomas' 9th grade reading and math scores to NaN (not a number).  This will prevent my program from crashing and allow the math to be done smoothly on the other school's values.

### Tasks 
- Replace the math and reading scores for Thomas High School with NaNs.
- Repeat the school district analysis.
- Find how these changes affected the overall analysis.

## Resources

    - Data sources: schools_complete.csv, students_complete.csv
    
    - Software/Languages: Jupyter Notebook 6.4.5, Python 3.9, Pandas 1.3.4
    

## Results

### Original Results

   #### Top 5 Schools
    
   ![Top Five Schools - Original](https://user-images.githubusercontent.com/33010018/150061075-9179d51e-cb76-493a-b470-45cca6194d54.png)
      
   
   #### Bottom 5 Schools
    
   ![Bottom Five Schools - Original](https://user-images.githubusercontent.com/33010018/150061111-0d3996ca-376b-4581-ab79-11e1118216a4.png)
       


### New Results (Removal of Thomas Highschool's 9th grades scores)

   #### Top 5 Schools
   
   ![Top Five New](https://user-images.githubusercontent.com/33010018/150061664-bb66b942-fcbd-41b2-8d9b-b316245f9235.png)

   
   #### Bottom 5 Schools
   
   ![Bottom Five New](https://user-images.githubusercontent.com/33010018/150061752-16c9c534-f2a7-4f8e-a6dd-2f592bfd2acb.png)


## Summary

### Original Analysis
The top 5 schools were all Charter and the bottom 5 were all District.  The Charter schools had less students than the District.   The overall passing percentage was at least 90% for the top 5 schools.   Each school had a better reading passing percentage than math. Overall, schools with 2000+ students have a very low passing percentage.
    
    
### New Analysis (Removal of Thomas Highschool's 9th grades scores)
    - The overall percentage slightly decreased.
    - Average math and reading scores slightly decreased. 
    - Math percentage slightly decreased.
    - Reading percentage decreased
    - Thomas High School remained in the top 5 performing schools.  There was a slight overall percentage decrease with the new results.
    - The schools with less than 2000 students continued to have a better performance overall.
    - Budget isn't a factor, schools with very high budgets are still in the bottom 5.
    - Charter schools remained the top performers.

