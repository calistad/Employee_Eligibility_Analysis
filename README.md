# Employee Eligibility Analysis

## Overview

We will provide analysis to help future-proof Pewlett Hackard Company for the “Silver Tsunami”.

### Purpose

- To determine how many people will retire and, of those employees, who are eligible for a retirement package. 

- To determine the number of retiring employees per title and identify employees who are eligible to participate in a mentorship program.

## Results

- retirement_titles.csv

  ![截屏2021-10-01 下午3 39 14](https://user-images.githubusercontent.com/88747464/135682393-0fcf7dd8-8727-4967-9ea4-fcc95443a57d.png)

  - There are duplicate entries for some employees because they have switched titles over the years. 

- unique_titles.csv

  ![截屏2021-10-01 下午3 39 54](https://user-images.githubusercontent.com/88747464/135682449-50779d8a-5e88-4fbc-ab11-40ab53d52e37.png)

  - Thus it’s helpful to use the ‘distinct on’ method to remove these duplicates and keep only the most recent title of each employee.

- retiring_titles.csv

  ![截屏2021-10-01 下午3 28 18](https://user-images.githubusercontent.com/88747464/135681886-6fb77dac-3119-4725-ae7b-aaaf87fe20fb.png)

  ![截屏2021-10-01 下午3 29 36](https://user-images.githubusercontent.com/88747464/135681898-5b895cd1-1c21-477b-b2e0-d726b63043e2.png)

  - The total retiring employees are 90,398, and the total employees in the company are 300,024.
  
  - The company still has about 70% of employees left.
  
  ![截屏2021-10-01 下午3 44 33](https://user-images.githubusercontent.com/88747464/135682859-34763712-9d8d-4f13-9702-5f09c79f3ce9.png)

  - There are only 1549 eligible employees for mentorship that were born in 1965, which are too few for mentoring around 90,000 new employees in the future.

## Summary

There are more employees needed for mentorship, we can retrieve employees that were:

![截屏2021-10-01 下午4 29 38](https://user-images.githubusercontent.com/88747464/135682632-d32b3bef-0f39-4337-b8df-6c65ee91293d.png)

- born in 1956, since the oldest to retire was born in 1955;
- Started to work in the company between 1980 to 2000, which should have enough experience for mentoring;
- Still work in the company.

![截屏2021-10-01 下午3 55 24](https://user-images.githubusercontent.com/88747464/135682647-9979938c-641a-4492-a5bc-7e028cddf454.png)

Upon these requirements, There are 161,050 eligible employees. 

There are completely enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees.
