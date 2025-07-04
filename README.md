# PostgresSQL_Retail_Sales_Data_Pipeline-Analytics

#### Tech Stack:
  - PostgreSQL
  - pgAdmin
  - CSVs


<br> 


#### Step 1: Created the database. 

![Image](https://github.com/user-attachments/assets/7b33b3f7-546c-412b-8fe6-3778512122d5)



<br>



#### Step 2: Data ingestion 
Loaded the CSV file online_retail dataset including changing the invoice column data type that was before 'timestamp' which is now 'VARCHAR' and removed the index column because of loading errors. 


![Image](https://github.com/user-attachments/assets/484b70d5-10f0-4155-91d8-d0c831efec42)



#### This was the copy command I ran in the psql tool editor.

<br> 

![Image](https://github.com/user-attachments/assets/04949748-5b35-416c-a76e-7219e1e506f7)


<br> 



#### I Confirmed that the data was loaded
Ran some select statements.  


<br> 


![Image](https://github.com/user-attachments/assets/7e4fd6ee-b6aa-4248-b6de-8ccbed1f730d)


<br> 


![Image](https://github.com/user-attachments/assets/b46f6d03-9474-4f55-b515-c86eac05b9a5)


<br> 

![Image](https://github.com/user-attachments/assets/2d683bf9-0f36-4ea5-8087-8afe30fec13a)


<br> 


![Image](https://github.com/user-attachments/assets/f991b9a9-aa08-4046-8e30-16e1f4d2ccf3)


<br>


![Image](https://github.com/user-attachments/assets/52405893-47ca-414c-afa3-a66869056cf6)


<br> 


![Image](https://github.com/user-attachments/assets/3dab6a52-5cda-4353-ab97-020ea286b121)


<br>



#### Step 3: Transforming the data
Data cleaning, and preparation for analysis.



<br> 


![Image](https://github.com/user-attachments/assets/6c2fb930-2740-40bf-8e0b-0bbd2192926f)


<br> 



![Image](https://github.com/user-attachments/assets/3c2b935f-4732-40df-8408-a27a2d0cc40f)


<br> 


There are no more null values and now they are under 'unknownID', I ran the previous select statement and the data output shown zero nulls. 


<br>


![Image](https://github.com/user-attachments/assets/797ae335-c40b-4da3-aeec-fa37030bd5fd)


<br> 


![Image](https://github.com/user-attachments/assets/16d720ac-c031-45bd-b1df-e2a31fff935f)
