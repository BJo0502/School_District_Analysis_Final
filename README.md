
# Module 4: PyCitySchools with Pandas

## Overview of the school district analysis

For the purpose of this Challenge, we are tasked to provide support to Maria, a chief data scientist who works for a city school system. Previously, we supported Maria by preparing the schools’ standardized test score data to be used for future trend and pattern analysis. Upon further a review, we have been informed that the data shows evidence of academic dishonesty so we most modify our data to not include the school and grade in question as the scores impact the total results for the district. We have been asked to repeat the district analysis without including Thomas High School’s 9th graders test results.

## Results: 

### How is the district summary affected?

Thomas High School (THS) is the 2nd highest performing school in the district. After removing the 9th grade results of this school from our analysis, we can see that the overall district results decrease slightly; however, THS remains the 2nd highest performing school. Although the district reading scores drop slightly, we see that removing THS' 9th grade results has a slightly greater impact on the math results, ultimately impacting the overall passing % as well. We notice that some of the results do not change such as the Total Schools and Total Budget. Since we only converted the 9th grade students' math and reading scores from THS to NaN, the Total schools and Total Budget results are not impacted. This makes sense since THS is still a school in the district and the current budget allocated to the school remains intact (at least as of now). While we are not instructed to convert the Total Students column to NaN, it is best practice to display the change in student count for the sake of the District Summary since the input of this column directly impacts the rest of the statistical columns.

![DistrictSummary](https://user-images.githubusercontent.com/88041368/133296352-f8770519-00c0-4747-ae4e-791541e06147.png)

### How is the school summary affected?
