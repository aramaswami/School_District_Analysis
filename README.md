# School_District_Analysis
I have included the following .ipynb files for the exercise presented in this module:
- PyCitySchools in two versions: (i) integrated (with all code in one cell); and (ii) showing segments (code segments for specific analyses in different cells)
- PyCitySchools_Challenge in two versions: (i) integrated; and (ii) showing segments.

The challenge requires the exclusoion of 9th grade math and reading scores. i used the .loc and np.nan operators to select the rows that correspond to that grade and set the value to NaN. This changed various aspects of the school district's summary results, as I've described below.

#### NOTE: The per_school summary and spending_summary tables generate correctly in my notebook but for some reason the display is not teh same way in github. The code is correct as far as I can tell.


Following are my responses to assignment questions about how excluding 9th grade impact results across school- and district-level analyses. Please note that the 'showing_segments" versions show how each table varies due to teh exclusion.

### How is the district summary affected?
While average scores are not too different after the exclusion, the pass rates for math, reading, and overall are down by about 30%. This indicates that 9tjh grade results were skewing the results significantly.

### How is the school summary affected?
School summary is affected similarly. Based on overall pass%, Rodriguez had the weakest overall score exclusing 9th grade, but ends up in the top 5 without 9th grade results. Cabrera was the top school when 9th was included but slipped to the second worst performer when they wer excluded.

### Recalculate the high- and low-performing schools.
Please see segmented code for results.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?
Thomas was not as significantly impacted, moving from #2 to #3 when 9th grade results were excluded (based on overall passing%).

### Recalculate the scores by grade, scores by school spending, scores by school size, and scores by school type.
Please see segmented code for results.

### How does replacing the ninth-grade scores affect the following? Math and Reading Scores by Grade, Scores by School Spending, Scores by School Size, Scores by School Type
Individual scores by math and reading are excluded in the challenge assignment. Reviewing the data suggests that the reduction in overall pass% is similiar across schools of different sizes (student population), per student spending, and type of school.
