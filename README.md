# **Why Does My Grandmother Buy Her Movies?** :movie_camera:
### **1. Introduction**
> This project will outline the aspects of film that influence whether or not my grandmother will purchase a physical copy of a movie. I will do this by taking a dataset of IMDB's movie database, which is updated quarterly, and comparing it to the physical copies of movies in my grandmother's basement.

### **2. Use**
> This visualization set will be able to show what aspects of movies would be most likely to influence the purchasing behaviour of one consumer (my grandmother) specifically. A similar methodology could be applied to other specific consumers to see what the strongest influences are on those other consumers.

### **3. Objective or Concept**
> Part of the objective of this visualization will be to help my grandmother better understand her preferences in movies and part of it will be to create an accessible template for analyzing consumer taste in movies. I'm going to create a transferable template for inputting a consumer's movie collection or viewing history to give them a visual way to assess and understand their own preferences in movies.

### **4. Problem Statement**
> My grandmother has a lot of movies in her basement and up until now has only been able to organize her movies collection by sorting them alphabetically and writing down what movies she buys in a notebook that she's had for years. I want to create a database that I can quickly look up for her if she has a movie already. From this database, I want to be able to give her a visualization of her collection and a breakdown of what aspects of those movies will determine if she purchases it or not. In creating this database and visualization for my grandmother, I am also making a template that I can use in the future for consumer movie purchasing behaviour.

### **5. Data:**

- I am using the [IMDB dataset](https://www.imdb.com/interfaces/) from the IMDB website for the primary dataset to retrieve the basic movie information. 

- I have created a column within the dataset to indicate if my grandmother has a movie or not. I have created this column to represent only feature films so this column does not include made-for-tv movies or television shows. 

- I will also be adding onto the dataset if a movie has won an [Academy Award](https://en.wikipedia.org/wiki/List_of_Academy_Award-winning_films) retrieved from Wikipedia.

### **6. Use Case**

My visualization is a very consumer specific idea that will assess the individual person's preferences and help them to understand their own purchasing behaviour better.

### **7. Scope**
    
- I am going to clean up the original IMDB dataset and the Academy Awards dataset using both PANDAS, JUPYTER notebooks, SSIS in Visual Studio and then finally in SSMS. 
- My goal is to do the initial exploratory data analysis and combining of the three datasets within PANDAS, save the full dataset into a CSV. 
- I haven't yet determined if I wish to use SSIS in between EDA and SQL. 
- After the preparation of the datasets, I will add a column at the end that will indicate whether my grandmother has the movie in her collection using binary values of 1 and 0.
- Once all the data is prepared, I will create a star schema using SSIS. I want to create a visualization using either PowerBI or Tableau. I haven't determined if I want to try a new program for visualization or really focus on PowerBI.
