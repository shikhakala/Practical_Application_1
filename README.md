## Assumptions:
1.	In column “Bar” value ‘less1’ is 1.
2.	Replaced `50plus` with `50` and `below21` with `20` in column `age`.

#### Actions taken for missing values:

  * Dropped 74 duplicate rows
  * Dropped column “Car” as it has around 99% missing data and was not relevant for analysis.
  * Replace missing values in categorical column "Bar" with mode value
  * Replace missing values in categorical column "CoffeeHouse" with mode value

#### Actions for data handling:

  * Rename column name "Passanger" to "Passenger"
  * Replace '(' and ')' to blanks in column Passenger
  * Handle strings in age column
 
![image](https://github.com/user-attachments/assets/7606481c-4281-48ad-a5be-f442186d37b0)

---
## Coupon general findings:
![image](https://github.com/user-attachments/assets/8e3ba4e2-9c1d-4d07-aa01-07bed1e30347)

1.	Coupons for “Carry out & Take away” and “Restaurant(<20)” have highest acceptance rates than Coffee House and then others.
 
![image](https://github.com/user-attachments/assets/074376c4-ba11-45aa-841e-e960e7e32514)

2.	Maximum number of coupons were accepted when temperature is 80 and least when temperature is 30.
 ![image](https://github.com/user-attachments/assets/f6c81482-ce11-4f10-83e3-812b56c007b2)

3.	Most of the drivers who are not going to \nany urgent place are accepting the coupons
4.	Drivers going to home and work have almost similar acceptance rate.

 ![image](https://github.com/user-attachments/assets/183ca482-3606-488e-bbf4-ee712ad107a1)

5.	Drivers who are travelling alone are accepting the coupons most and then drivers travelling with friends.
6.	Acceptance rate for drivers travelling with kids in .50 
7.	While drivers travelling with Partner have little more acceptance rate than Kids

![image](https://github.com/user-attachments/assets/9b95b006-7ff7-48e3-9a8c-52375e89e2c6)

 
8.	Most of the drivers are accepting the coupons when expiration date is of 1 day
9.	Coupons getting expired in 2h have acceptance rate of almost .50.

![image](https://github.com/user-attachments/assets/755dd15a-9c45-4dad-b897-a763770adb1b)

 
10.	Drivers who are single or \nMarried partner are mostly accepting the coupons.
11.	Drivers who are widowed are less likely to accept coupons.

 ![image](https://github.com/user-attachments/assets/3ceff2ba-885e-440f-8dd0-2784c00c894e)

12.	Drivers who are unemployed or Student as occupation are mostly accepting the coupons

 ![image](https://github.com/user-attachments/assets/97532bdc-1d56-402f-88d6-0f50194377bc)

13.	Drivers who have more income are less likely to accept the coupons
14.	Drives with low income are mostly accepting the coupon.

 ![image](https://github.com/user-attachments/assets/fa61412d-57af-4a88-9c90-a07cd70c7d90)

15.	Drivers who take CarryAway between 1 to 8 times are most likely to accept the coupons than others

 ![image](https://github.com/user-attachments/assets/6b656dba-dc53-4541-a53b-5590dc0e4037)

16.	Drivers who go to cheap restaurants atleast once in a month are more likely to accept the coupons

 ![image](https://github.com/user-attachments/assets/1494309d-3773-4ea3-aa53-e0a6390541da)

17.	Drivers who go to luxury restaurants more than 3 times are less likely to accept the coupons


# Investigating the Bar coupon

![image](https://github.com/user-attachments/assets/aa56efcb-1ef4-4a20-b5ed-2df7d29b8106)

1.	Drivers who go to bar more than 3 times are more likely to accept the coupons than those who went less than 3 times.

![image](https://github.com/user-attachments/assets/c7ecef07-e6ee-441c-8345-eb325c6c205e)
 
2.	Driver who go to bar more than once a month and has age greater than 25 are more likely to accept coupons than all others.

 ![image](https://github.com/user-attachments/assets/28ab2e15-62d3-443c-b2cb-c15e06fce0ad)

3.	Driver who go to bar more than once a month and has no kids and has occupation other than 'Farming Fishing & Forestry' are more likely to accept coupons than all others.
 
![image](https://github.com/user-attachments/assets/0ab0f215-4a2f-4052-90ab-648ff1b802f9)

4.	Drivers who visits cheap restaurants more than 4 times a month and \n income is less than 50K are less likely to accept coupon' than drivers who go to bar more than once and has no kids passengers and were not widowed and has age < 30

---

### Findings for Bar coupons data:

•	Driver who go to bar more than once a month and has age greater than 25 and has no kids and has income less than 50k are more likely to accept coupons than all others.
•	Driver who go to bar less and has age less than 25 and has kids and who has income more than 50k are less likely to accept coupons.

---

## Investigating coffeehouse coupons:


 ![image](https://github.com/user-attachments/assets/b5a94153-806b-4e69-a14c-32e7f8534137)

1.	Driver who go to coffeehouse more than 3 times are more likely to accept the 
Coupon
 
![image](https://github.com/user-attachments/assets/4dd00ed4-6cc0-4b69-a445-e39dfaf78696)

2.	Driver who go to coffeehouse atleast once and is female and has partner as passenger is more likely to accept the coupon than male drivers who are travelling with partners.

 ![image](https://github.com/user-attachments/assets/c2bb337e-748c-4712-adcd-0b8c05b85300)

3.	Female driver who go to coffeehouse atleast once is more likely to accept the coupon than all others

![image](https://github.com/user-attachments/assets/800698d2-679c-4e15-9b9a-85af5c737a20)
 
4.	Driver who go to coffeehouse atleast once a month and is travelling alone with no urgent places to go to is more likely to accept the coupon than driver going home

 ![image](https://github.com/user-attachments/assets/d794adb3-cff1-4201-87b4-0b54dd68e3ce)

5.	Driver who visit coffeehouse atleast once a month , married, travelling with partner and going home is more likely to accept the coupon than driver who is travelling alone

 ![image](https://github.com/user-attachments/assets/7e05309a-d2de-4f9e-bbb6-2d9f92788194)

6.	Driver who visit coffeehouse atleast once and has income less than 50k is more likely to accept the coupon than drivers who has income more than 50k.

![image](https://github.com/user-attachments/assets/9aa548da-dfe8-44a6-a113-249e116d1058)
 
7.	Driver who visit coffeehouse atleast once and has no children is more likely to accept the coupon than driver who has no children.

 ![image](https://github.com/user-attachments/assets/4a3ca34e-d1da-47d3-a5ae-c8379149b230)

8.	Driver who visit coffeehouse atleast once and is student is more likely to accept the coupon than driver who is not student.
---
## Findings for Coffeehouse data:
•	Drivers who visit coffeehouse atleast once and are student or unemployed or has no children or income less than 50k or is married and travelling with partner and is going home or travelling alone and going to non urgent places and are female are more likely to accept the coupons
