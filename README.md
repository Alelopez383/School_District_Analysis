# School_District_Analysis
Analysis on standarized tests scores and student funding using Jupiter Notebook, Pandas and Numpy Library.

# Overview of the school district analysis: 
We are tasked to provide insights about the performance trends and patterns for spending and performance in several high schools. These insights will provide information for the discussion and strategic decisions at the school and district level for spending bills ans standarized tests.

Therefore, an analysis was carried out at the District level, by school, by school grade, by budget granted, by size and type of school.

However, stemming from a possible grade conflict or possible fraud at Thomas Middle School, it was requested that all the 9th grades be dropped, which implied a change in the results of the previous analyzes. In particular, caused changes in the results at the school level THS, at the district level the effect was marginal.

# Results: 

## 1. How is the district summary affected?
We can observe that initially, the changes to eliminate the grades of the ninth grade of the Thomas High School, did not show strong implications at the district level, since the math and reading averages remained unchanged, as well wiwth the percentages of passing math, reading an overall.
 
The District summary with the 9th grades students of Thomas High School:

![image](https://user-images.githubusercontent.com/43974872/190064831-a00e5c7f-05b3-4e77-9c3d-50156ae66720.png)

The District Summary without the 9th grades of Thomas High School:

![image](https://user-images.githubusercontent.com/43974872/190062943-ad77326f-9f61-49d9-a23d-4b4cf8530f09.png)

## 2. How is the school summary affected?

At the school level, the removal of THS's 9th grade tests did not have any implications for the other schools. However, we can see that in terms of the percentages of students passing in math, reading and overall passing the school had a strong withdrawal of approved students if the 9th grades are out of the countability. The drop in the percentage of students who passed math, falls 26.36 percentage points; reading falls 27.65 percentage points; and the overall passing, drops 25.87 percentage points.

Thomas High School summary without 9th grades:

![image](https://user-images.githubusercontent.com/43974872/190067628-2e43f96c-da67-4f2a-aa14-2777cb9f90c4.png)

Thomas High School summary without 9th grades:

![image](https://user-images.githubusercontent.com/43974872/190066340-61783fd3-e4cd-4dc3-8ee4-74e4841ae8b9.png)

The School summary complete:

![image](https://user-images.githubusercontent.com/43974872/190065978-88c56ed9-202e-4983-b390-24f04aed588d.png)


The School summary without the 9th grades of Thomas High School:

![image](https://user-images.githubusercontent.com/43974872/190065497-b2d8f664-1a31-4fff-b64c-b5bbf9cde484.png)


## 3.How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
One of the main implications of removing grades from the ninth grade was the drop in positions with respect to other schools; because when those grades were included, THS ranked as the second school with the highest percentage of students passing. Now, without the 9th, it ranks ninth out of 15.

Top 5 schools complete:
![image](https://user-images.githubusercontent.com/43974872/190071070-e0a9bb75-33e9-4cf1-85be-df9d074a7484.png)


However, if only the grades of the other grades (10th-12th) are taken into account, it is shown that THS continues to be the school with the second highest number of approved students; so if there is any question of fraud in the 9th, the results of the other grades could corroborate that in fact, said grades remain in accordance with the level of the school in general.

Although they did raise the approval percentages a little, they were marginal.

Top 5 schools (without counting 9th grades):

![image](https://user-images.githubusercontent.com/43974872/190070866-ad6b0f1a-6a71-4059-b376-71eb7828dc64.png)

## 4. How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
When looking at the implications of eliminating the 9th grade math grade, we see that it only affects THS. The same goes for reading scores; and the other grades of the school remain the same, since they have no implication whatsoever.

Math Scores by grade, incluiding 9th THS:

![image](https://user-images.githubusercontent.com/43974872/190205608-1b6f738d-21e9-4039-8c67-f9b583f6eb24.png)

Math Scores by grade, without 9th THS:

![image](https://user-images.githubusercontent.com/43974872/190205708-1974be60-1ff2-4783-98c6-7944118b90ed.png)

Reading Scores by grade, incluiding 9th THS:

![image](https://user-images.githubusercontent.com/43974872/190207110-a92bc104-8152-4b10-bfe1-eca073f13b94.png)


Reading Scores by grade, without 9th THS:

![image](https://user-images.githubusercontent.com/43974872/190206557-878a704c-a054-4f34-96f7-ba021eb45c7d.png)

### Scores by school spending

THS has 1,635 students, so the cost per student is $638 each. The school has an average of 83.42 in math and 83.85 in reading. Meanwhile, the percentage of students with approved mathematics is 93.27%, which is quite high. In the same sense, there is reading, with a percentage of 97.31%, which postulates it as the best school in reading. Regarding the percentage of approval in general, this is 90.95%, ranking as the second best school.

The spending per student of $638 dollars, places THS as a school with a medium-high expenditure per student ($631-645), however, it is higher in approvals, since the average for schools with this expenditure is 63% and THS is at 90.63%

Scores by school spending:

![image](https://user-images.githubusercontent.com/43974872/190208493-fb935654-660d-4bc3-a1a9-f3ab0166bde2.png)

Scores by spenging ranges:

![image](https://user-images.githubusercontent.com/43974872/190208699-bacd5e3b-8d55-43cf-a6c1-455180147ed1.png)

### Scores by school size
Now, in terms of school size, THS ranks as a mid-size school.
In this sense, the percentages of THS approved due to its size show that they are slightly below the average.
However, schools of its type show much better passing rates

![image](https://user-images.githubusercontent.com/43974872/190213468-9a0d8a66-a1ae-43e5-b4a9-bc500ba9cc80.png)

### Scores by school type
If we take into account the type of school, THS type is Charter, the school is just in the passing average.
![image](https://user-images.githubusercontent.com/43974872/190214000-2c38cd27-4eb2-41e1-805b-4506af743a58.png)

# Summary: 

In summary, the main changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs are:

1. Eliminating THS's 9th grades does not have significant implications, as THS students show higher percentages in passing math, reading an overall passing; which could imply that there was no fraud in the tests of the 9th graders.
2. Removing 9th grades does affect the school's ranking among schools, if we count their absences in the overall count. However, if we remove these and focus on 10th, 11th and 12th grades, the school's position among the other schools ranks as the second best school, second only to Cabrera High School. Position he was in before removing the grades from 9th grade.
3. The TSH spends $638 dollars per student, however, the ratio of spending and approval percentage is high; that is to say that the THS has managed to exceed the average levels of students approved with the budget granted.
4. Due to the size of the school, the size ratio and percentages of students approved, it is in the average range. They don't stick out.
5. Meanwhile, the relationship between type of school and percentages of approved students, THS is slightly above expectations.

