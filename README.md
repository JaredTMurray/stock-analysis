# stock-analysis
### Module 2 VBA Macros
#### Refactor VBA Code and Measure Performance
##### Deliverable 1:
In this module, I prepared an assignment in which the code was made more efficient through refactoring. I iterated all the rows and created a new index variable which was set to zero, then completed three arrays in two different types. 

I looped over all the rows in the spreadsheet and created a loop that initialized ticker volumes to zero. A script was written that increases the current stock ticker volume variable and adds the ticker volume for the current stock ticker.

If-Then statements were written to check if the current row was both the first and last row, with the selected ticker index. The next row’s ticker was made to not match the previous row’s ticker. 

A for loop was created to output the “Ticker,” “Total Daily Volume,” and “Return” columns in the spreadsheet.

Finally, two images were created for the stock analysis outputs for 2017 and 2018.
For a detailed analysis of all work please see the [VBA_Challenge.xlsm](https://github.com/JaredTMurray/stock-analysis/blob/main/VBA_Challenge.xlsm).

Written Analysis of Results
#### Overview of Project:
The purpose of the refactoring was to make the code more accessible and simpler to understand for Steve. It generated results based on nested loops, for loops and formatting of the previous information in the stock analysis VBA macros.

#### Results:

The results here contain the 2017 and 2018 Total Daily Volumes and Returns for Steve and which ones were successful or not using the refactored code. 
* The returns remain the same in both years irregardless whether the original code or refactored code was used.
* ENPH and RUN were the only 2 positive returns Steve had for his stocks at 81.9% and 84% respectively. 
* It took approximately 0.1171875 seconds for the code to run for the year 2017
* It took approximately 0.0234375 seconds for the code to run for the year 2018.


![2017 Total Daily Volume and Return](https://github.com/JaredTMurray/stock-analysis/blob/main/2017.png)

![2018 Total Daily Volume and Return](https://github.com/JaredTMurray/stock-analysis/blob/main/2018.png)

#### Summary: 
The advantages of refactoring code include the fact that code can be sampled from a much larger dataset, it is more time efficient in execution; in terms of gathering data from nested loops, for loops and if-then statements and in general makes the script run faster, and finally it provides more relevant data from the dataset for the user to interpret in an intelligeble manner. 
The disadvantages include possibly corrupting previous code through changes made from expansion of data set and varibles, and that the code for the project may have been better for the user in question in the first place and should not have been changed.

The advantages and disadvantages when contrasted side by side for both the original and refactored VBA script include:
* Advantage of original: less of a large dataset to draw from for Steve's initial summations of daily volumes and returns regarding his tickers. His total volume for   the current ticker was simpler to obtain.
* Advantage of refactored VBA script: more of a large dataset to draw from for Steve's initial summations of daily volumes and returns regarding his tickers. His increased volume for the current ticker is now more obtainable.

* Advantage of original: The starting price and the ending price for the current ticker could be gotten simpler
* Advantage of refactored VBA script: The current row can be checked now to view if it is the either the first row with the selected ticker index or the last row with the selected ticker index.

* Advantage of refactored VBA script: The time spent is a bit less for both years (2017) 0.1171875 seconds and (2018) 0.0234375 seconds in terms of running the code to get Total Daily Volume and Returns.

* Disadvantage of original: less relevant data from the dataset is provided. For instance only Tickers is used as an array, whereas with the refactored vba script uses tickers, tickerVolumes, ticketStartingPrices and ticketEndingPrices as arrays. Thus less detailed analysis can be carried out. 
* Disadvantage of refactored VBA script: more data from dataset is provided however, less information about starting and ending prices for tickets is obtained. Instead the nested loop contains information whether the current row is the first or last row with the selected tickerindex. 
