# Indian Cars EDA
A dataset containing 1276 rows and 141 columns containing the details of Indian cars is cleaned column-wise and explored.

## Data Cleaning Process Outline
**Categorical Columns**, depending on the circumstances, have been dealt with in four ways:

1. The Nulls have been filled with the mode
2. The data is too varied for the nulls to be filled with mode, so nulls have been filled with empty strings. *Example:* Basic warranty column has extremely varied data with no landslide majority.
3. Columns with 'Yes' and Nulls have had nulls replaced by 'No'.
4. Based on the column name and car feature availability across the models in the market, specific null values have been replaced with 'No'. *Example:* The Power Steering column had multiple types of power steering listed along with null values. Since not all cars have power steering, the nulls were replaced with no.

**Numerical columns** were cleaned after removing extra string characters, converted to float or int datatypes and nulls were filled with the measures of central tendency.

## EDA Outline
1. Numerical column analysis through descriptive statistics and heatmaps
2. Car makers and models were analysed based on ex-showroom prices, and the top and bottom models were visualised.
3. Price Category was created and visualised
4. Histograms of primary numerical columns that are relevant for car purchase decisions were made.
5. The yes/no columns containing many extra features that are spread across the dataset were plotted in pie charts to see which columns are present in what percentage of cars

# Challenges 
The large amount of columns made it a challenging task to clean the dataset. The columns had to be cleaned meticulously. Although some column cleaning could be done through a user-defined function, most columns had different anomalies that had to be dealt with manually. Consideration had to be made in understanding the nature of the column and its relevance to a car.

# Future Steps
This dataset can be further explored by choosing a particular car, such as the Tata Nano Genx or Mercedes-Benz B-Class, and individually exploring the details of the makers and models.
