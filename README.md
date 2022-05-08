# School District Analysis
## Overview of School District Analysis
### Purpose
A school district board has recently learned that some of the data used in their analysis of schools in the district was compromised. Said data was the 9th grade math and english test scores from Thomas High School. In order to maintain integrity of the report, the school board needs the school district analysis to be redone.
### Task
I was tasked with removing the affected part of the data (9th grade math and english test scores from Thomas High School), and repeating the analysis which included the following:
1. The district summary
2. The school summary
3. The top 5 performing schools
4. The bottom 5 performing schools
5. The average math scores by grade level for each school
6. The average reading scores by grade level for each school
7. The scores by spending per student
8. The scores by school size
9. The scores by school type

## Results
Removing the compromised data changed the analysis in the following ways:

### District Summary
Previous district summary:
![image](https://user-images.githubusercontent.com/102445183/167283820-d48ffb33-a1d7-429b-80d8-178bc97f15d0.png)

New district summary:
![image](https://user-images.githubusercontent.com/102445183/167239644-30b07191-a3ee-433a-967b-119fb8bc11ce.png)

- slightly lower average math score
- slightly lower passing math percentage
- slightly lower passing reading percentage
- slightly lower overall passing percentage

### School Summary
Old school summary:
![image](https://user-images.githubusercontent.com/102445183/167283911-bb7636ef-0360-43de-9a57-5c234306d1f6.png)

New school summary:
![image](https://user-images.githubusercontent.com/102445183/167239693-3a3e7f0c-9217-4e5f-8c1b-84d1338225e3.png)

- slightly lower average math score
- slightly higher average reading score
- slightly lower passing math percentage
- slightly lower passing reading percentage
- slightly lower overall passing percentage

### Thomas High School Performance
Thomas High School's overall performance was lowered slightly, but their ranking compared to the other schools stayed the same, being ranked second among all the schools in overall passing percentage.

### Math and Reading Scores by Grade
Old math and reading scores:

![image](https://user-images.githubusercontent.com/102445183/167284097-1a8d4f11-0e58-4057-aee4-e0fe821009a9.png)
![image](https://user-images.githubusercontent.com/102445183/167284101-099d8755-4c84-4b3a-a290-45462b4d060b.png)

New math and reading scores:

![image](https://user-images.githubusercontent.com/102445183/167239696-61c6587e-708c-4fa6-902c-e4187c4b2417.png)
![image](https://user-images.githubusercontent.com/102445183/167239704-db55d410-000c-45e5-b15a-6da5a77a0fb8.png)

- 9th grade math and reading scores at Thomas High School were replaced with "nan"
- Other grade's math and reading scores were unaffected

### Scores by School Spending
Old scores:

![image](https://user-images.githubusercontent.com/102445183/167284120-276c76a8-18dc-4033-b6c1-370ee41acea6.png)

New scores:

![image](https://user-images.githubusercontent.com/102445183/167239727-4645b701-73df-4f54-a8b0-f81eb6c84b22.png)

- The scores by school spending were unaffected (within signficant range)

### Scores by School Size
Old scores:

![image](https://user-images.githubusercontent.com/102445183/167284127-84cb2876-23f6-4a16-918d-fa9fe7d10d35.png)

New scores:

![image](https://user-images.githubusercontent.com/102445183/167239736-71758987-3300-46e8-8bd7-4cdbaa7769e2.png)

- The scores by school size were unaffected (within signficant range)

### Scores by School Type
Old scores:

![image](https://user-images.githubusercontent.com/102445183/167284141-afb11bc3-bec6-416f-95fa-01f3ef13aa6f.png)

New scores:

![image](https://user-images.githubusercontent.com/102445183/167239747-280b1a35-7cb3-411a-8ef9-5af117de7662.png)

- The scores by school type were unaffected (within signficant range)

## Summary
### Change 1
Replacing Thomas High School's 9th grade math and reading scores with nan values affected the district summary by lowering the average math score, math and reading passing percentages, and overall passing percentage.
### Change 2
Replacing the scores with nan values affected the school summary by lowering Thomas High School's average math score, increasing their average reading score, lowering their math and reading passing percentages, and lowering their overall passing percentage.
### Change 3
Replacing the scores with nan values removed that data from the table on math and reading scores by grade for Thomas High School, but didn't affect any of their other math and reading scores by grade data.
### Change 4
Replacing the scores with nan values did not significantly affect the analysis on scores by school spending, scores by school size, or scores by school type.
