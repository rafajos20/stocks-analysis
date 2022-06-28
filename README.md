# VBA CHALLENGE
## The Purpose:

The purpose of this analysis is to determine the return for the entire stock market over the last few years and determine whether the stocks are worth investing and help Steve to perform an analysis at the reach of a click. Steve needs to know which are the percent of return for the different stock markets each year and the total volumes that they obtained; this will provide to Steve a solution for save time for enjoy him personal life. 

## The Refactored Script:

The first step refactoring the code was creating a ticker index and set to equal to zero.
 
Following for create the three output arrays tickerVolumes as long and tickerStartingPrices and tickerEndingPrices as Single. we have 12 different variables for ticket in the data so between the parenthesis the number 12 for refer it. 			
 

Then, I used the tickerIndex and the output arrays for define the conditions, starting with an “IF” to validate that the ticker is the same as the one referenced in the index. The last part to refactoring is use the same expressions and conditions we used in the module but use the ticker index and the arrays into to the expressions.
 

all this is reflected in the execution times of the original script compare the refactored script reduce considerably for the year 2018 past of 0.83 seg to 0.09 seg.

/stocks-analysis/resources/VBA_Challenge_2017.png  



and for the year 2017 past of 0.96 seg to 0.11 seg
  



## The Advantages:

*Save time because it decreases execute run time in macro.
*Save space in memory using the right variable types. 

 ## The Disadvantages:

* The main disadvantage is that you need to transform an already created code that is working correctly for one that allows you to obtain other benefits.

## Summary 
Refactoring the Code helps to correct previous programming errors helping the code to be faster and more organized. this directly influences in the design, software improvement, debugging, and faster programming. Refactoring helping it to be more efficient, it could be a powerful tool in terms of programming helping to save time and money, however, it could have disadvantages, these disadvantages may range from having applications that are too large to not having the proper test cases for the existing codes, which may ultimately pose some risk if we try to refactor our code.

