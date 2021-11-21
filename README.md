# School_District_Analysis

REPORT

1.	Overview of the school district analysis: Explain the purpose of this analysis.
The purpose of this analysis was to omit the scores which may have been tainted by academic dishonesty, and repeat the analysis of the test scores from this school district.  




2.	Results: Using bulleted lists and images of DataFrames as support, address the following questions.

o	How is the district summary affected?

The district summary now has a fewer number of students and therefore a lesser budget. However, there would be an increase in average scores and passing percentages because of increase in scores from Thomas High School after the omissions.

o	How is the school summary affected?

The whole school summary is not affected very much. Only the scores and percentages for Thomas High School are affected, now showing a significant increase in each of those categories.

o	How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Thomas High School’s performance shows a significant increase after omitting the ninth graders’ math and reading scores. Sorting the DataFrame by Overall Passing Percentage in descending order, we can see the Thomas High School is now in the top five best performing schools. Omitting the ninth graders’ scores boosted Thomas High School up to second on the performance list, behind Cabrera High School.
 
o	How does replacing the ninth-grade scores affect the following:

	Math and reading scores by grade

Math and reading scores by grade are not affected. These tables group each school by the average scores in each grade. Removing the scores for only ninth graders in one school, does not affect other grades in the same school or any other school at all.

	Scores by school spending

Thomas High School’s budget per student is approximately $638, and therefore it falls in the $630-$644 spending bin. Because of the significant increase in scores for Thomas High School after the omission of ninth graders’ scores, this results in a significant increase in scores and passing percentages for the $630-$644 spending bin. For example, we can see an approximately 8% increase in Overall Passing Percentage for the $630-$644 bin.

	Scores by school size

Thomas High School falls in the Medium bin, with school size of 1000-2000 students. Therefore, this bin showed significant increases in scores and passing percentages. For example, there was an approximately 6% increase in Overall Passing Percentage for the Medium bin.

	Scores by school type

Thomas High School falls in the Charter bin, and after the omission of ninth graders’ scores, the Overall Passing Percentage for this bin showed an approximately 3% increase.



 
3.	Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

In summary, the four major changes to the updated school district analysis after the scores for ninth graders at Thomas High School were omitted are as follows:
1.	Thomas High School is now the second highest performing school in the list.
2.	Schools spending $630-$644 per student show an 8% increase in performance.
3.	Schools of Medium size with 1000-2000 students show a 6% increase in performance.
4.	Charter schools show a 3% increase in performance. This marginal increase is because all other Charter schools already had high performances in terms of Overall Passing Percentage. Therefore, this suggests that, in general, Charter schools may have a higher performance than District schools.
