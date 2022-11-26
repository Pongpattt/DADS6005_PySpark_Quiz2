This repository was created for quiz2 in DADS6005 subject (Topic: PySpark)

## Quiz2_1

- Table1 & 2 (from Kafka database)

![image](https://user-images.githubusercontent.com/50355214/204098152-3bde06fe-e0b8-4250-a91f-1078717f65f3.png)

- Join Results 

![image](https://user-images.githubusercontent.com/50355214/204098190-71bd9a42-378b-4cba-aeb3-168d612d2c5d.png)


## Quiz2_2

Send 2 messages (table1: num_click (1st and 2nd), table2: Country(1st)) in same time.

- For Example:
  Time: 2022-11-26 18:32:30  >> data come in as show below

![image](https://user-images.githubusercontent.com/50355214/204104456-1c7af63e-76ee-4272-97dc-01b16441e4db.png)

  Then, next 5 seconds at Time: 2022-11-26 18:32:35
  
![image](https://user-images.githubusercontent.com/50355214/204104538-93b72c2c-7b12-4126-b76d-f5463a9a960b.png)

  the data of these 2 interval periods are calculated and summarize by country as below.
  
![image](https://user-images.githubusercontent.com/50355214/204104628-1d9e2524-ae59-4f80-ad3e-7ccd61ae8891.png)

** last image is technically illustrated at Time: 2022-11-26 18:32:30.



The members of group:
1. 64xxxxxx06 
2. 64xxxxxx13 
3. 64xxxxxx20
