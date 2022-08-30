**Executive Summary**

**Problem Statement**:	
	Representation, including diversity and inclusion, is very low for minorities in America in colleges and universities. Therefore, there is a discussion that the best way to improve diversity and inclusion at colleges, especially Ivy league, is to help eliminate one of the minoritys' earliest obstacles: the SAT/ACT. As we know that the SAT's/ACT's are required for college admission statewide, but research shows that the highest population of minorities in America has the lowest participation scores as well as test scores too. I will be focusing on the African American community as my sample size because they are currently the highest population within the minority compared to Hispanics and others. 

	Princeton University's admissions board has hired me to figure out the best ways to eliminate minorities' most significant college admission obstacles: the SAT/ACT scores. Therefore, I will be asking and answering the question of "How to increase African American admissions to their college by elimination or editing their SAT/ACT requirements?". In addition, Princeton University wants to increase representation, diversity, and inclusion in colleges to be a model for other colleges statewide. 
	
	To do my job efficiently, I will be focusing mainly on the African American community data population statewide, their SAT/ACT score,  and their participation. 

**Background**
Of course, the SAT/ACT is a foundational part of the college admission process within America. It's known worldwide that a low score from these exams can cost you your admission to your top college/university choice. Although, for minorities in America, this is a common theme as data shows African Americans and other minorities except for the Asian race perform poorly on these exams compared to their white counterparts. Throughout time, there has been the question as to why this happens. Another question that is popularly asked is: "Is the SAT/ACT rooted in systematic racism?

So let us take a moment to step back to who created the exams in the first place. Carl Brigham started the SAT/ACT in 1926 to test intelligence and college readiness, but people do not know that Brigham was a faithful "eugenicist". A eugenicist is a person who believes their race is superior and should not mix with others, especially with the negro race. Considering this, the SAT/ACT did not consider nor tailored to include minorities. I bring this up because society in America has tried to diminish the African American community with discrimination in all aspects of life over time as such examples of "redlining." 
	
 As the SAT/ACT evolved throughout the years, college admissions have denoted a decrease in applications from African American students and low participation for the SAT/ACT. For example, Princeton University stated that African Americans only accounted for a staggering 8% of the student population. Understanding this statement, colleges are now asking what they can do to help increase the African American community admissions starting with SAT/ACT requirements. 
(Source: https://www.nea.org/advocating-for-change/new-from-nea/racist-beginnings-standardized-testing)

**Description of Data**
I have used five (5) data sets to answer my problem statement within my analysis.
1. data set used is act_19.csv includes the states, participation rates, & average scores by state.

2. data set used is sat_19.csv includes the states, participation rates, & average scores by state.
	Source: Given in Vscode
3. Outside Source 1 - Black Population combined with act_19.csv. This includes the population of the African American community by the state in combination with act_19 scores and participation
 
4. Outside Source 2- Whole Minority Population in America. This includes Blacks, Asians, Indians, etc. 

5. Outside Source 3 - The Black Population Percentage within States. This includes the African American population in percentage by the states.
*Sources are stated at the end*

**Data Dictionary**
|Feature|Type|Dataset|Description|
|---|---|---|---|
|df_ACT19|object|ACT_19|This is required data chosen|
|df_SAT19|object|SAT_19|This is required data chosen|
|df_TestedBlack|object|Outside Source|Data set to show ACT score & Black population together|
|df_USBlack|object|Outside Source|Data set showing only minority population in the world|
|df_OnlyBlack|object|Outside Source|Data set showing only African American population in the world|
|df_ACT19float|object|Outside Source|Converting the pariticipation rate to a float|
|df_SAT19float|object|Outside Source|Converting the pariticipation rate to a float|

**Summary Statistics**
From the histogram created it shows that Participation levels within the ACT were high when there is only 100% participation. Although when compared to the states where African Americans had a high populations were low.
From the scatterplot created, it showed that less populated areas of African Americans had lower ACT scores.
The heatmap of the df_USBlack shows negative correlations between the minorities compared to their white counterpart


**Recommendations**
From the data analyzed within the notebook:
Colleges/Universities should consider a student's environmental and socioeconomic status
Sponsor creative, affordable SAT/ACT prep courses and college-bound programs starting with elementary to Highschool
Redefine the definition of "College Readiness" to engage youth to participate more
Most importantly, erase the assumption that everyone has equal access to education, no matter their race

**Conclusion**
To answer the problem statement above, Princeton University will have to reduce the required test scores to compensate for more African American students to admit within their university. Why? With my findings, race/ethnicity has a significant and substantial effect on SAT/ACT scores, performance, participation, and environment compared to White counterparts. The African American community, especially in the southern states, scored low with meager participation rates through my data visualization and correlations. Once we understand this principle, we can make the necessary adjustments to create more inclusive admission requirements for people of color.

**Sources**
https://www.nea.org/advocating-for-change/new-from-nea/racist-beginnings-standardized-testing
https://www.ednc.org/eraceing-inequities-the-influence-of-race-on-sat-scores/
https://www.brookings.edu/blog/up-front/2020/12/01/sat-math-scores-mirror-and-maintain-racial-inequity/
https://reports.collegeboard.org/pdf/2020-total-group-sat-suite-assessments-annual-report.pdf
https://www.insidehighered.com/admissions/article/2019/09/24/minority-and-first-generation-sat-scores-fall-behind
https://www.insidehighered.com/news/2015/09/03/sat-scores-drop-and-racial-gaps-remain-large
https://www.usnews.com/news/best-states/slideshows/the-10-states-where-students-are-the-most-prepared-for-college?slide=2