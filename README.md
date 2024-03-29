# UCB-Data-Analysis-Challenge-2
    Creator: Henry Jinghe Chen  Date: 2/15/2024
## Project Description
    The project is created for UCB Data Analysis Challenge 2.
### The Functionalities:
    *Runs on all worksheets in the workbook
    *Collects the tickers of the stocks in the worksheets
    *Calculates the yearly change of each stock in the worksheets
    *Calculates the percent change of each stock in the worksheets
    *Calculate the total stock volume of each stock in the worksheets
    *Formats the original sheets to meet the requirement that improves readability
    *Formats annual percent changes, greatest percent increase, and greatest percent decrease into percentages
    *Format the greatest total volume increase into scientific notation with two decimal places
    *Format the cells of yearly change and percent change according to increase(Green) or decrease(Red)
### Code Description
![alt text](Code1.png)

The first few lines of code actualize the function that allows the script to run through all the worksheets.
Following that, the script formats the sheets and cells.
Then, the code adds the titles.
After that, the code creates some key variables that will be used.

![alt_text](Code2.png)

This section of the code is to analyze the data row by row to find the sections of each stock in the data.
Then, it put in the tickers for the stock.
After that, it calculates the yearly changes, percent changes, and total stock volume.
The next section of the code compares the values to the existing largest or lowest values to find whether the current value is the greatest percent increase 
greatest percent decrease, or the greatest total volume.
If they are, the corresponding cells will be updated with their information

## Results
### Multiple Year Stock
![alt text](2018.png)
![alt text](2019.png)
![alt text](2020.png)
### Alphabetical Testing
![alt text](imgA.png)
![alt text](imgB.png)
![alt text](imgC.png)
![alt text](imgD.png)
![alt text](imgE.png)
![alt text](imgF.png)
