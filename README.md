# Deforestation Exploration
**Udacity SQL Nanodegree Project 1**. Data analyst for ForestQuery, a non-profit organization on a mission to reduce deforestation around the world and which raises awareness about this important environmental topic.

## Steps to Complete
1. Create a **View** called **“forestation”** by joining all three tables - **forest_area**, **land_area**, and **regions** in the workspace.
2. The **forest_area** and **land_area** tables join on both **country_code** AND **year**.
3. The **regions** table joins these based on only **country_code**.
4. In the ‘forestation’ View, include the following:
   - **All of the columns of the origin tables**
   - A **new column** that provides the **percent of the land area that is designated as forest**.
5. Keep in mind that the column **forest_area_sqkm** in the forest_area table and the **land_area_sqmi** in the land_area table are in **different units (square kilometers and square miles, respectively)**, so an adjustment will need to be made in the calculation you write (1 sq mi = 2.59 sq km).

## Part 1 - Global Situation
### Instructions:
- Answering these questions will help you add information into the template.
- Use these questions as guides to write SQL queries.
- Use the output from the query to answer these questions.

a. What was the total forest area (in sq km) of the world in 1990? Please keep in mind that you can use the country record denoted as “World" in the region table.

b. What was the total forest area (in sq km) of the world in 2016? Please keep in mind that you can use the country record in the table is denoted as “World.”

c. What was the change (in sq km) in the forest area of the world from 1990 to 2016?

d. What was the percent change in forest area of the world between 1990 and 2016?

e. If you compare the amount of forest area lost between 1990 and 2016, to which country's total area in 2016 is it closest to?

## Part 2 - Regional Outlook
### Instructions:
- Answering these questions will help you add information to the template.
- Use these questions as guides to write SQL queries.
- Use the output from the query to answer these questions.
- Create a table that shows the Regions and their percent forest area (sum of forest area divided by the sum of land area) in 1990 and 2016. (Note that 1 sq mi = 2.59 sq km).

Based on the table you created:

a. What was the percent forest of the entire world in 2016? Which region had the HIGHEST percent forest in 2016, and which had the LOWEST, to 2 decimal places?

b. What was the percent forest of the entire world in 1990? Which region had the HIGHEST percent forest in 1990, and which had the LOWEST, to 2 decimal places?

c. Based on the table you created, which regions of the world DECREASED in forest area from 1990 to 2016?

## Part 3 - Country-Level Detail
### Instructions:
- Answering these questions will help you add information to the template.
- Use these questions as guides to write SQL queries.
- Use the output from the query to answer these questions.

a. Which 5 countries saw the largest amount decrease in forest area from 1990 to 2016? What was the difference in forest area for each?

b. Which 5 countries saw the largest percent decrease in forest area from 1990 to 2016? What was the percent change to 2 decimal places for each?

c. If countries were grouped by percent forestation in quartiles, which group had the most countries in it in 2016?

d. List all of the countries that were in the 4th quartile (percent forest > 75%) in 2016.

e. How many countries had a percent forestation higher than the United States in 2016?