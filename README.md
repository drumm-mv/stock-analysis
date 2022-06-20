# Stock-analysis

## Overview of Project

### Purpose of Analysis
To read through a list of stock quotes and return a table showing the total Value as well as Return on investment percentage for the following stock tickers: "AY", "CSIQ", "DQ", "ENPH", "FSLR", "HASI", "JKS", "RUN", "SEDG", "SPWR", "TERP", "VSLR
In addition to expand upon the original requested script we have refactored the current code to increase processing speed. Although the current code works well for a dozen stocks, it might not work as well for substantially larger lists stocks; it may take a long time to execute.

## Results

### Conclusions for Refactoring Code
After refactoring the code for the analysis still produces the output as expected.  But with the benefit of a drastic increase in processing speed.

![image_name](/resources/Final_analysis_2017.png) ![image_name](/resources/Final_analysis_2018.png)

The following images show the processing speed of the original script while running analysis for 2017 (left) and 2018 (right) followed by the processing speed after refactoring.

![image_name](resources/VBA_Challenge_2017_Org_Code.png) ![image_name](resources/VBA_Challenge_2018_Org_Code.png)

![image_name](resources/VBA_Challenge_2017.png) ![image_name](resources/VBA_Challenge_2018.png)

## Summary
### Advantages and Disadvantages of Refactoring Code

|Advantages|Disadvantages|
| --- | --- |
|Removed redundancies and duplications<br>improve the effectiveness of the code|Imprecise refactoring could introduce<br>new bugs and errors into the code<br>|
|Improved legibility improves the<br>comprehensibility of the code for other<br>programmers|There is no clear definition of “neat code”<br>|
|Restructuring the code is possible<br>without altering the functionality|The benefit is not self-evident;<br>Improved code difficult for user to recognize<br>when the functionality stays the same|

Click [here](https://www.ionos.com/digitalguide/websites/web-development/what-is-refactoring/) to see the article that the above advantages and disadvantages of refactoring were borrowed from. The article is related to web-development but the list can be applied here as well.

 - How do these pros and cons apply to refactoring the original VBA script?







