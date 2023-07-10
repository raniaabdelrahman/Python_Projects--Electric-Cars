### Business problem

Greenwish Ltd needs a new fleet of sales rep cars for the UK.
Employees, shareholders, clients and customers all want electric v ehicles considering the 
large millage done by reps ev ery year.
Greenwish Ltd’sboard needs to make a decision, but it must be based on data.
Use the dataset 'evdataset.csv'supplied to perform your analysis.
1. Which make and model to buy?
2. Which factors/variables are relevant to the decision?
3. Show your conclusions with persuasive visuals


----------------------------------------------------------------------------------------------------------------

### Project Summary

**The steps that are taken to conclude the result are as follow:**

1. Some data cleaning processes are made to check for null values, duplicates or any other issues. The data was clean and has no issues.

2. Assumptions are made as follows:
    * The main factor to consider is the mileage which is displayed in the data in the weather columns.
    * We only need to consider the combined - mild weather for the mileage, because it gives an average mileages for the cars on the city and high way. The cold wather doesn't need to be considered because it's based on the -10 Celsius and it's not quite common in the UK.
    * Other irrelevant columns have been dropped such as Link.
3. Data is being grouped by the make column.

4. To find out which variables are most relevant to the mileage, the correlation analysis between the combined mild weather and other variables is done. 

5. The result of the correlation analysis showed that the most relevant variables that could affect the car mileage are as follows:
    * Electric Range
    * Battery Capacity
    * Top Speed
    * Total Power
    * Fastcharge Speed
    * Acceleration 
6. The final step was to combine all the revelevant variables to compare the different makes and find out which are the top recommended. 
7. As we can see from the above Chart, the the best car makes that are recommended to be bought, considering the mileage and the factors that are affecting it, are as follow:**

    * **Porsche**
    * **Gensis**
    * **Kia**
    * **Tesla**
    * **Huyndai**
