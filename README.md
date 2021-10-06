# Movies_ETL

## Overview of the analysis:

We help our friend Britta to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables.

### DELIVARABLE #1 
-  We want to write an ETL Function to Read Three Data Files
    
  ![8 1 movies df](https://user-images.githubusercontent.com/87447639/136244999-5d2b6228-c541-4663-b010-274163f7d54e.PNG)
  
  ![8 1 kaggle metadata](https://user-images.githubusercontent.com/87447639/136245011-e2909351-b394-4e53-ba12-af9f1c32dab7.PNG)
  
  ![8 1 ratingsdataframe](https://user-images.githubusercontent.com/87447639/136245018-1d8473a2-0eb9-4725-8672-9f583d1054fc.PNG)


### DELIVARABLE #2

- We want to create Extract and Transform the Wikipedia Data

  ![8 2wiki movies](https://user-images.githubusercontent.com/87447639/136245530-bae239f1-aad5-42d5-8f9a-46325c28a72d.PNG)
  ![8 2 wikidf](https://user-images.githubusercontent.com/87447639/136245693-d2f71d5b-9eee-4d70-b1a8-700b7c9c1378.PNG)


### DELIVARABLE #3
 - We want to extract and Transform the Kaggle data

  ![8 3 movies df](https://user-images.githubusercontent.com/87447639/136245961-b473ac37-de49-437c-8950-6955650107de.PNG)


### DELIVARABLE #4

- We want to create the Movie Database and load the data to a PostgreSQL Movie Database

  ![deli#4](https://user-images.githubusercontent.com/87447639/136244246-4cb2958d-16e0-4b5f-8f0f-cbece75903c1.PNG)



## Results:

We were able to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

  ![moviestable100](https://user-images.githubusercontent.com/87447639/136244283-d111b6a7-9842-42d4-be57-96372cee6954.PNG)
  