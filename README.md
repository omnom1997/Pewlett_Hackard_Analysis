# Pewlett Hackard Analysis

## Overview 
We were intially tasked with helping Bobby perform employee research to determine who is eligible for a retirement package and which positions will need to be filled in the near future. This analysis was to help future-proof Pwelett Hackard as well as help update Pewlett Hackard's methods to use SQL. Our next task was to determine the number of retiring employees per title and to identify employees who are eligible to participate in a mentorship program.

## Results
### Deliverable 1 Results

![retiring_titles](https://user-images.githubusercontent.com/114427019/206307143-0d334b93-d031-4f91-8d83-819fe22992d6.png)

- Many of the employees who are eligible for retirement are in staff to mid-level management positions as shown below in the image above of the retiring_titles.csv
- Two of the five managers are retiring over the next few years
- The majority of employees retiring are in Senior positions

### Deliver 2 Results

![mentorship_title](https://user-images.githubusercontent.com/114427019/206318152-ced57d0a-cc33-48c3-8cdf-08add8176ff8.png)

- 1,549 employees are eligible for the mentorship program 

## Summary 

### How many roles will need to be filled as the "silver tsunami" begins to make an impact?

Overall, 72,458 roles will need to be filled as the "silver tsunami" begins to make an impact. Due to the initial analysis including employees with birthdays over a span of four years, it's not likely that all 72,458 employees will retire at once. We can refactor our query used in part one of the first deliverable to parse out employees that are likely to be leaving over the next four years based on their birth day. The adjusted query is pictured below. After running the adjusted query, we could then re-perform the same analysis we did for our first deliverable on the new tables.

![Extra query 2_1](https://user-images.githubusercontent.com/114427019/206314011-0a377ef3-88b7-493e-a434-25f98757ff39.png)
![Extra query 2_2](https://user-images.githubusercontent.com/114427019/206314024-a1f0f05d-fd95-4611-b730-102ef4ed4640.png)



### Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees? 

The simple answer is there will be enough retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees. The new mentee class would have to be paired with the last group of retirement-ready employees, ie. the employees born in 1955, to give the mentee class enough time to learn from their mentors. As we can see, the image on the left is the number of mentees per job title and the image on the right is the number of retirement ready employees with born in 1955. There will be enough qualified retirement-ready employees to mentor the next generation.

![Extra query 1](https://user-images.githubusercontent.com/114427019/206314817-e52c27ef-9293-40a9-b7f4-cf63f8c3046d.png)
![Extra query 1_2](https://user-images.githubusercontent.com/114427019/206315833-8831dcc4-cac2-4193-b756-08d4423b7851.png)

