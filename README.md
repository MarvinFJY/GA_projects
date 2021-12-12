### Project 1: Standardized Test Analysis
---
Given that one of the Key Performance Indicator (KPI) of the College Board is to improve participation rates of standardized tests. I will be examining recent trends made by the 2018-19 SAT & ACT cohorts to find out which state(s) should the College Board focus their effort and resources on in order to improve SAT participation rates and also taking note that the increase in participation rate should not drastically decrease overall college acceptance rate.

### Background
---
American College Testing (ACT) is a standardized exam that high school students take in college admission readiness in the US. High schools, colleges, universities, and education departments in states use the ACT scores in comparing students’ applications for admission.

ACT Inc. conducts the exam to evaluate the student’s readiness for college, while the College Board (the largest NPO in the US that helps navigate the transitioning from high school to college) conducts the SAT exam.

In 2010, the College Board introduced a program called SAT School Day that was meant to increase access to the SAT for low-income students by giving them free tests on weekdays and in their own schools. Although the program caught in a few places, the SAT was not as widely accepted as an assessment test because it's generally considered to test aptitude rather than knowledge.

However, the redesigned SAT (released in 2016) that aims to overhaul the existing format to align the SAT with Common Core standards (i.e. a set of educational standards for American Schools, from kindergarten through 12th grade, designed to be consistent between each state and district), making it more appealing as an assessment test than its o lder version.

### Summary of Analysis
---
Trends that we had observed:

- Participation rates and total mean score / composite have a strong negative correlation
- Participation rates in SAT and that of ACT have a strong negative correlation
- ACT composite scores in 2018 and that of 2019 have a strong positive correlation while SAT total scores in 2018 and that of 2019 have a strong positive correlation
- There is however minimal impact on median score for both SAT and ACT even if participant rates changes

### Summary of Conclusions & Recommendations
---
As it is ultimately the decision of the state to make it a requirement for all its students to take either the SAT or ACT, the College Board could only do so much in encouraging students to opt for taking the SAT rather than ACT or local state tests. The College Board has been successful thus far in raising its SAT participation rates and in raising the number of states requiring student to take the SAT (from only 3 states in 2014-15 to 10 states in 2017-18 <sup>[(1)](https://reports.collegeboard.org/archive/sat-suite-program-results/2018/sat-school-day)</sup> ) through efforts such as the 'SAT School Day' in 2010 and redesigned SAT in 2016. It is only a matter of time until the SAT gains popularity and more states recognises the value making SAT a statewide test requirement. 

Hence, I would recommend focusing efforts on states that have already made SAT a requirement for all its students and in addition, states that have shifted its requirement away from taking the ACT.

Some measures for the College Board would include:
- visits to schools to educate students on the importance of taking a standardized test
- hold conferences and road shows for parents to share success stories of children graduating from colleges
- hold talks and provide brochures on comparisons between an globally recognised test and a local state test
- expand the SAT School Day partnership to South Carolina or to reduce the SAT fees further to encourage the state to adopt statewide SAT testing and encourage students to choose the SAT over other tests

### Data Dictionary
---
|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|ACT/SAT|State names for 50 states in the US| 
|act_participation_2018|float|ACT|State participation rate for ACT in 2018| 
|act_composite_2018|float|ACT|State mean composite score in 2018| 
|act_participation_2019|float|ACT|State participation rate for ACT in 2019| 
|act_composite_2019|float|ACT|State mean composite score in 2019| 
|sat_participation_2018|float|SAT|State participation rate for SAT in 2018| 
|sat_ebrw_2018|int|SAT|State mean score for Evidence-Based Reading and Writing (EBRW) in 2018| 
|sat_math_2018|int|SAT|State mean score for Math in 2018|
|sat_total_2018|int|SAT|State mean total score in 2018| 
|sat_participation_2019|float|SAT|State participation rata for SAT in 2019| 
|sat_ebrw_2019|int|SAT|State mean score for Evidence-Based Reading and Writing (EBRW) in 2019| 
|sat_math_2019|int|SAT|State mean score for Math in 2019| 
|sat_total_2019|int|SAT|State mean total score in 2019|
