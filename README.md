# Refactor-VBA-Code-and-Measure-Performance
## Overview of Project: Explain the purpose of this analysis.
The purpose was to create a program for a friend that analysis 12 different stocks from 2017-2018. Thus help deciding which trends are worth investing. 
## Results: Using images and examples of your code, compare the stock performance between 2017 and 2018, as well as the execution times of the original script and the refactored script.
 Based on the return of the stocks from 2017 to 2018, in 2017, all stocks except for TERP, had a positive return. In 2018, ENPH and RUN had a positive return. Based on the data, ENPH would be a good stock to choose from since it has been positive for two consecutive years. 
![Alt text](https://i.imgur.com/HtGwFWg.jpg)
###
When originally creating the script, the response time of the output of return between various years was 0.38 seconds. By editing the code to search by ticker indexes, it became faster and efficient. By refactoring the code, one can add more data and therefore analyze more data. The code ran in 0.09 seconds for the year 2017.
### Orginial code
![Alt text](https://i.imgur.com/RgTnNLe.jpg)
### Refactored
![Alt text](https://i.imgur.com/j3NyZGP.jpg)
###
![Alt text](https://i.imgur.com/Gss3Aow.jpg)
### Summary: In a summary statement, what are the advantages or disadvantages of refactoring code?
The advantages of refactoring the code, for the end user, is that it makes the expereicne better because the code is fresh, efficient, and faster. When the code crashes or has time delays, the code can become useless. From the coders stand point, when one needs to debug, it will be easier to read and easier to maintain. 
Disadvantage may be that it is time consuming. If the code works, it works. Another disadvantage is in the process, one can accidentally create a bug. 
### How do these pros and cons apply to refactoring the original VBA script?
When refactoring the code, it was challenging knowing how to complete the process and approcach it the solution. The process was time consuming in trying to figure out the problem. For example, assigning the three output arrays and including the indexes. This component was difficult to figure out. 
The pro of refactoring is that the code ran three times faster than before, it is now ready to analyze the entire stock market.  

