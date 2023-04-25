# pandas-challenge

The most difficult part of this challenge was the "School Summary" dataframe where we needed to include several series that were grouped by school name by utilizing the "groupby" method in Pandas. 

I went over our sorting example from class and determined that I would need to group each calculation by the school name, apply a function to each of the statistics I needed to evaluate, then reference the column we need to apply the fuction to. The result would return the below: 

![image](https://user-images.githubusercontent.com/128104435/234388117-34a67976-2c70-4f9e-b530-f41554e766cb.png)

I had to first make sure that each column of the summary dataframe printed exacly the same way, with the 15 school names as "keys" on the left and the values for each calculation on the right. 

Like so: ![image](https://user-images.githubusercontent.com/128104435/234386488-baa8bb08-1635-4e58-8a17-2399a4fafb02.png)

Once I confirmed that each of the columns were printing correctly, I was able to create the summary by school dataframe and have it correctly print. 
