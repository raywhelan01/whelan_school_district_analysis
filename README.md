# whelan_school_district_analysis

### Module 4 Challenge

In this module's challenge we are asked to invalidate the math and reading scores of 9th grade students at Thomas High School due to the grades having been tampered with. We are then asked to run a series of analyses to report on how the grade invalidation affects a series of summary statistics across the district.

#### How is the district summary affected?

By dropping the Thomas High 9th graders scores, the average math score of the districted dropped by .1% while the average reading score was not substantively affected. The percentage of students passing math, passing reading, and passing overall drop each by ~1%, the amount corresponding to the share of Thomas High 9th graders who had passing scores before their scores were dropped.

#### How is the school summary affected?

By dropping a quarter of the students scores, the percentage of students passing math, reading, and overall dropped each by approximate;y 25%. The average math score dropped by ~.05% while the average reading score actually jumped by the same amount.

#### Does removing the math and reading scores affect Thomas High School's performance relative to other schools?

Yes, Thomas High drops from the second highest performing school to the lowest performing school. This drop is due to the fact that the overall passing percentage, by which the school are ranked, includes the dropped students (whose scores are effectively zero for this ranking) in the school's average. The ranking should be tweaked to completely disregard these students in the average to truly assess Thomas High's performance.

#### Math and Reading Scores by Grade:

In our tables summarizing the average scores for each school by grade-level, there are no changes other than the Thomas High 9th grade entry being replaced by 'NaN'. However, by creating new tables that average grade level scores across the district, we find that 9th graders average math score has dropped .2% to 78.7% and the reading score has dropped nearly .1% to 81.8%.

#### Scores by School Spending:

The average scores in math and reading for the $630-$644 range (Thomas High's bucket for per student spending) have not changed, however, the percentages of students passing math, reading, and overall have dropped by ~7%.

#### Scores by School Size:

The average scores for students in medium sized school's (Thmas High's size classification) has not changed, but the percentages of students passing math, reading, and overall have dropped by ~6%.

#### Scores by School Type:

The average scores of Charter school students has not changed, but the percentages of students passing math, reading, and overall have dropped by ~4%.