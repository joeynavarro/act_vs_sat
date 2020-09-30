# SAT & ACT Analysis for 2017 & 2018

##### Project Completed By: Joey Navarro



##### ![image info](test_taker.jpg)

Photo by [Green Chameleon](https://unsplash.com/@craftedbygc?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/students-testing?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText)

***



# Problem Statement

Participation rate changes have been recorded for both the SAT and ACT exams between 2017 and 2018. This report explores the reasons for the these changes within the United States categorized by test and subject. 



***




# Executive Summary

### 2017 Data Import & Cleaning
Errors such as extra characters were corrected and percentages were removed to convert all numerical data in numbers with decimal points. 

### 2018 Data Import and Cleaning
Data was found to match the data fields of 2017's data. The cleaned-up data from both 2017 and 2018 were combined to a single data frame for the ease of comparison. 

### Exploratory Data Analysis
The standard deviation for each numerical variable were calculated using three different methods. The highest and lowest states were identified in terms of participation rates and scores. 

### Data Visualization
Histograms, box plots, heat maps and scatter plots were used to investigate the data and correlations further. 

### Descriptive and Inferential Statistics
Most of the statistics have a close-to-normal distribution. Although the data points add up to more than 30, more data points would further ensure a closer-to-normal distribution for the numerical variables used in this report. 

### Outside Research
Research has been undertaken from the official State Education Departments and other related articles. Some of these include the details of state policies with regards to the compulsory taking of the exams and/or the sponsoring of test fees. 

### Conclusions and Recommendations
State departments of education play a pivotal role in increasing the test participation rates. This can come in the form of state subsidies for the test or making the taking of the test mandatory for all school students. The states of West Virgina, Ohio, Rhode Island and Illinois are examples of such policies which greatly impacted SAT participation rates. The SAT Test Day, which happens on a regular school day also contributed to an increase in the overall SAT participation rate. 

Focus on collaboration with state education departments, colleges and high schools would likely lead to the continued increase in SAT participation rates. 

More research can be done on university admissions criteria in the U.S, SAT test centers and their usage to helps understand how to further drive participation rates. 

***

# Project Directory

```
ACT Against SAT
|--data
		|--act_2017.csv
		|--act_2018.csv
		|--sat_2017.csv
		|--sat_2018.csv
|--combined_2017.csv
|--combined_2018.csv
|--final.csv
|--README.md
|--sat_and_act_analysis_for_2017_and_2018.ipynb
|--sat_and_act_analysis_for_2017_and_2018.pdf
|--tableau_viz
		|--act_participation_2017.png
		|--act_participation_2018.png
		|--sat_participation_2017.png
		|--sat_participation_2018.png
|--test_taker.jpg
```



# Data

#### Provided Data

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)
- Note: 2019 scores were provided with the original work but overlooked them when creating the presentation and working on the code so they are not included

#### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*string*|ACT/SAT|The state in the United States of America.|
|**sat_participation or act_participation**|*float*|ACT/SAT|The percentage expressed as a float on the number of students enrolled in schools|
|**sat_reading_and_writing**|*float*|SAT|The average English reading and writing score in a maximum score of 800.|
|**sat_math**|*float*|SAT|The average math score in a maximum score of 800.|
|**sat_total**|*float*|SAT|The combined score of sat_reading_and_writing and sat_math.|
|**act_english**|*float*|ACT|The average math score in a maximum score of 36.|
|**act_math**|*float*|ACT|The average math score in a maximum score of 36.|
|**act_reading**|*float*|ACT|The average reading score in a maximum score of 36.|
|**act_science**|*float*|ACT|The average science score in a maximum score of 36.|
|**act_composite**|*float*|ACT|The average score calculated by the 4 ACT scores of each state.|



***



# Conclusions and Recommendations

#### Key Takeaways

Based on the data, major movements in participation rates are spurred on by the state department of education's policies. If a state were to mandate a requirement for all students to take a particular test, the participation rate for the rate would increase exponentially. From further research, I also found that implementation of such policies are usually met on with high opposition from the competition. 

Ohio state law requires districts and community schools to administer the state-funded ACT or SAT to all grade 11 students. This has resulted in an increase for participation for both ACT and SAT tests. 

Rhode Island has made SAT testing compulsory for all students. This was implemented between 2017 and 2018 and its effects can be seen in the SAT participation, from 71% in 2017 to 97% in 2018.

Illinois, like Rhode Island, has also made SAT testing compulsory for all public high school juniors. This has caused an exponential increase in SAT participation from 9% to 99%. The ACT participation rate was halved during this period. It should be noted that this move by the Illinois State Board of Education opposed this decision and is awaiting the final outcome. 

In West Virginia, the participation for SAT has doubled from 14% to 28% while ACT saw a decrease by 5%. This can be attributed to the education department's implementation of the SAT School Day where high school  students can take the SAT tests on an allocated school day rather than taking in on a weekend and usually at a test center which they do not school at. 

Between 2017 and 2018, 10 states (Colorado, Connecticut, Delaware, Idaho, Illinois, Maine, Michigan, New Hampshire, Rhode Island, and West Virginia) and the District of Columbia covered the cost of the SAT for all their public school students. Three years ago, only three states and the District of Columbia did so. This, and the implementation of the SAT School Day contributed to the overall 25% increase in SAT test-takers. 

As such, the SAT School Day and the cost subsidy of the SAT can be seen to greatly improve SAT participation rates. 

#### Recommendations

First its obvious that a states' department of education has the highest and most immediate impact on participation rates of a test. This would be in terms of a mandatory test in all schools within the state.

It is also paramount to maintain the working relationships with the states already implementing mandatory tests in their location. This would come in the form of customer service, reliability and efficiency in administering the tests and getting the results.

Success stories can also be seen in states where the education department subsidzes the full costs of the test, making them more accessible to lower income students.

The college board should explore working with both high schools and colleges. A college's admission criteria based on either of the tests' score would have an huge impact on the perceived value of the test. The value to colleges of a single type of test for the admissions criteria is that they have a single metric which they can rank their applicants by, rather than having to compare their over two sets of metrics. Colleges have also been observed to be moving away from standardized tests. This issue should also be addressed to prove the need for these tests in providing impartial information about their applicants.

Further research should be done on the university admissions criteria, the type of test and the scores students have been accepted upon and the composition of students taking both tests. Furthermore, information about the test centers and their usage could also shed some light on the matter. These would help to identify both tatical and strategic targets for College Board to further improve the SAT participation.

***



# References

Colorado SAT. (n.d.). Retrieved July 30, 2020, from https://www.cde.state.co.us/assessment/coloradosat

Genota, L. (2019, February 20). SAT Scores Rise as Number of Test-Takers Tops 2 Million. Retrieved July 30, 2020, from https://www.edweek.org/ew/articles/2018/10/31/sat-scores-rise-as-number-of-test-takers.html

PSAT10 and SAT School Day. (n.d.). Retrieved July 30, 2020, from http://www.ride.ri.gov/InstructionAssessment/Assessment/PSATandSAT.aspx

Rado, D. (2016, February 13). Illinois moves ahead with new testing plan, replacing ACT with SAT. Retrieved July 30, 2020, from https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html

SAT School Day (High School). (n.d.). Retrieved July 30, 2020, from https://wvde.us/assessment/sat-school-day-high-school/

State-Funded SAT Tests. (n.d.). Retrieved July 30, 2020, from http://education.ohio.gov/Topics/Testing/State-Funded-SAT-Test