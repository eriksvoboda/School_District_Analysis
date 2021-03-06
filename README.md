# School District Analysis

## Overiew of Project

After reviewing the test scores from the initial data, the school board believes that the reading and math grades at Thomas High School shows evidence of academic dishonsety. Specifically in the ninth grade. The purpose of this project is to first replace the ninth grade reading and math scores at THS with NaNs and then update the existing school distric analysis to account for the replacement of the ninth grade test scores at THS.

## Results

By replacing the test scores of the ninth grade at THS, this impacts the resulting summaries in different ways. 

- How is the district summary affected?
  
Within the district summary, and rouding to the tenths place; Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing decreased compared to the origianl PyCity analysis. Each of these metrics 0.1 - 0.2 decrease in score or percent, respectively. 
  
- How is the school summary affected?

Even after replacing the ninth grade test scores, THS remains in the top five schools. THS' % Overall Passing dips slighly from 90.95% to 90.63%. However it reamains the second highest school in terms of % Overall Passing.

- How does replacing the ninth graders' math and reading scores affect THS' performacnce relatiive to the other schools?

Even after replacing the ninth grade test scores, THS remains in the top five schools. THS' % Overall Passing dips slighly from 90.95% to 90.63%. However it reamains the second highest school in terms of % Overall Passing.

- How does replacing the ninth grade scores affect the following: 

  - Math and reading scores by grade
  
  Other grades average math and reading scores aren't affected by replacing the ninth grade scores at THS. When sorting school performance by grade for average math and reading scores, THS is at the bottom of the list when sorting for 9th grade from highest to lowest. 
  
  - Scores by school spending
  
  THS falls into the second largest spending range (per student) bin of $630-644. Replacing the ninth grade scores causes all metrics to improve in the $630-644 bin compared the data before ninth grade scores were replaced. For example % Overall Passing increases from 63% to 66%.

  - Scores by school size
  
  THS is a medium size school with a total of 1635 students. When looking at school performance by size there is no difference after replacing the ninth grade THS scores.

  - Scores by school type
  
  THS is a Charter school. Replacing the ninth grade scores does not affect the final summary by school type. If there were less Charter schools then the replacement of the ninth grade THS scores would have had a larger impact. But as we see the final summary isn't affected by this replacement. 

## Summary

By replacing the ninth grade scores a THS with NaNs there is slight decreases in all metrics, bar Average Reading Score, at THS. When looking at school type, all of the metrics are the same as before the ninth grade scores were replaced. The metrics in the School Size summary also do not change with the replacement of ninth grade THS scores. All metrics increase in the $630-644 bin, which THS is a part of, after replacing ninth grade test scores. 

### DataFrame Summary Photos

#### Replacing Ninth Grade Scores at THS
![](/Resources/ninth_grade_replaced.png)

#### District Summary DF
![](/Resources/District_summary_challenge.png)

#### THS Updated Metrics
![](/Resources/ths_updated_metrics.png)
