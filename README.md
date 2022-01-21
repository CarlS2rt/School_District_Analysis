# District Test Scores Analysis

This project is an analysis of standardized test scores in math and reading from across the district. The analysis breaks downs results by school and by grade level. In the course of the original analysis, the data suggested the possibility of academic dishonesty. The district requested a revised analysis omitting the results from Thomas High School's 9th grade class. As a result, Thomas High School's passing averages came down dramatically as the following analysis shows.

## Results

### District Summary:

The District-wide results were not greatly affected by the changes.  There were 461 students excluded from the overall analysis, which was not significant enough the create large swings in the District results. The original results are below:

![https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/district_original.png](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/district_original.png)

As seen in the updated District results below, any changes to the overall results were negligible:

![https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/district_new.png](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/district_new.png)

The results were more noticeable, however, as the dataset narrowed, as the remaining summaries will show.

### School Summary:

The school-level summary was only impacted inasmuch as Thomas High School data was removed. The original results showed Passing Percentages for each subject and overall in the 90s. With the ninth grades scores still included in the overall totals, we can see the impact of removing the ninth grade scores below:

![https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/school_new.png](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/school_new.png)

With the ninth grade data removed, Thomas High School's passing percentages decreased by approximately 30% in each passing category. This is not indicative, however, of how the other grade levels at the school performed. If you remove students with no grades from calculations, you will get a more representative sample of Thomas High School's overall performance:

![](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/school_new_updated.png)

### Thomas High School Impacts:

Once the results are scaled for a smaller sample of students without the Thomas High School ninth grade included, we see that the overall change for the school relative to the others less than half of a percentage point. The original top schools and their scores were as follows:

![](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/top_original.png)

 After removing the ninth grade scores and recalculating scores with the new student totals, Thomas High School remained the second highest performer with only slight drops in their average scores and passing percentages as shown below:![](C:\Users\carla\AppData\Roaming\Typora\typora-user-images\image-20220121154739338.png)

Other impacts of the changes are as follows:

- Math and reading scores by grade were unaffected beyond the removal of Thomas High School's ninth grade.
- Changes to scores by school spending were not manifest and remained unchanged as shown below:

![](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/spending_new.png)

- Scores by school size also remained the same as shown below:

  ![](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/size_new.png)

- Scores by school type did not show a noticeable change as well due to the small set of students removed from the calculations:

  ![](https://raw.githubusercontent.com/CarlS2rt/School_District_Analysis/main/images/type_new.png)

## Summary

To summarize, the changes were mostly insignificant due to the small number of students in Thomas High School compared to the District as a whole.  The changes are best summarized in the table below:

| Metric       | Average Math Score | Average Reading Score | % Passing Math | % Passing Reading | % Overall Passing |
| ------------ | ------------------ | --------------------- | -------------- | ----------------- | ----------------- |
| **Original** | 83.418349          | 83.848930             | 93.272171      | 97.308869         | 90.948012         |
| **New**      | 83.350937          | 83.896082             | 66.911315      | 69.663609         | 65.076453         |
| **Updated**  | 83.350937          | 83.896082             | 93.185690      | 97.018739         | 90.630324         |

The new score calculated with Thomas High School ninth graders still in the counts shows significantly lower passing percentages in all three categories and only minor differences in average score. From the average scores, you can deduce that Thomas High School still performed well despite the academic dishonesty in the ninth grade class. The updated scores, which remove the ninth grade from student counts, more accurately reflect Thomas High School's performance. Scores in the updated analysis on the 10th-12th grade differ from the original scores by less than 0.5% on the whole. 
