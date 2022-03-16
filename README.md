# School_District_Analysis

## Overview of the school district analysis
The purpose of the original assignment was to analyze school district data and report on key metrics. In the current scenario, it was determined that the data showed evidence of academic dishonesty related to Thomas High School’s 9th grade reading and math scores. I have been asked to replace those scores with NaNs (i.e., “not applicable”) and repeat the analysis of school district data to determine how the absence of these data affect the overall key metrics.

## Results

### How is the district summary affected?

Redacting Thomas High School’s 9th grade reading and math scores resulted in no change to district scores because Thomas High School is classified as a Charter school.

### How is the school summary affected?

The overall school summary shows very little difference when redacting Thomas High School’s 9th grade reading and math, reducing the overall score by 0.04%.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing Thomas High School’s 9th graders’ math and reading scores does not affect their performance relative to the other schools, other than not being able to compare 9th grade math and reading scores.

### How does replacing the ninth-grade scores affect the following:

#### Math and reading scores by grade

Replacing Thomas High School’s ninth-grade scores only results in the data reflecting NaNs, as shown for example:
 
![image](https://user-images.githubusercontent.com/97558998/158637922-1e90ecab-6a66-4fc3-9e74-30b95fb75a65.png)

#### Scores by school spending

Thomas High School falls into the “$630-644” Spending Range Per Student. Within this category, removing Thomas High School’s 9th grade reading and math scores made no difference when scores were averaged, and very little difference to percentages:
    
* % Passing Math -0.02%
    
* % Passing Reading -0.07%
    
* % Overall Passing -0.08%

Before excluding Thomas High School’s 9th grade scores:

![image](https://user-images.githubusercontent.com/97558998/158642936-de5ceac4-2f1e-45e2-8959-cb708f5febda.png)

After exluding Thomas High School’s 9th grade scores:

![image](https://user-images.githubusercontent.com/97558998/158643018-c3406632-b15d-4d62-b312-55cfa5e198b0.png)
    
#### Scores by school size

As Thomas High School is classified as a “medium” size school, the data for small and large schools show no change. The medium size schools show no difference in averages, and very little difference to overall passing rates:

* % Passing Math -0.02%

* % Passing Reading -0.06%

* % Overall Passing -0.02%

Before excluding Thomas High School’s 9th grade scores:

![image](https://user-images.githubusercontent.com/97558998/158643705-187eb779-bff5-46da-94fb-37ce4abeeae8.png)

After exluding Thomas High School’s 9th grade scores:

![image](https://user-images.githubusercontent.com/97558998/158643764-72eb3afa-99d2-457e-84b6-a1878d284dcc.png)

#### Scores by school type

There was no difference to District summary scores, as Thomas High School is categorized as a Charter school. Removing Thomas High School’s 9th grade reading and math scores made no difference when Charter scores were averaged, and very little difference to overall Charter School rates:

* % Passing Math -0.01%

* % Passing Reading -0.04%

* % Overall Passing -0.04%

Before excluding Thomas High School’s 9th grade scores:

![image](https://user-images.githubusercontent.com/97558998/158644022-a070aaa0-cb42-4672-bba6-22e6944d1fd6.png)

After exluding Thomas High School’s 9th grade scores:

![image](https://user-images.githubusercontent.com/97558998/158644066-60dd24fe-7896-4480-96ae-fbc29f86258f.png)

## Summary
The total number of students in the original database was 39,170; the number of students removed (i.e., Thomas High School’s 9th grade students) was 461, resulting in the current database of 38,709. This is equivalent to a reduction of 1.18% of data; it is not surprising that final results of this analysis revealed very little change overall. The data was evaluated based on school spending, school size, school type, and overall passing percentage; results of the re-analysis are as follows: 

* School Spending: overall passage rate decreased 0.08%

* School Size: overall passage rate decreased 0.02% in the medium size schools

* School Type: overall passage rate decreased 0.04% for Charter schools
