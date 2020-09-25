# Stock Performance Analysis

## Overview of Project

This project was designed to analyze a data set of publicly traded green companies in order to help my client make
and informed decision on which companies to invest in for their retirement portfolio.  I wanted to provide my clients
with yearly data on the volume of the company's stock that was traded and said companies yearly return on investment.

## Results

When initially looking at the analyzed data, there is a stark comparison to how well the green companies performed 
2017 and 2018. Using the color coding, it's easy to see all stocks had a positive ROI besides one. Then in 2018, every
company but two (ENPH and RUN) had a negative ROI at the end of the year.  With too many outside variables unaccounted for
in the data set and only two years worth of data, a statement of correlation or projection of how well the same stocks 
will do in the next year is not possible. Now, the most heavily traded stock out of the 12 in 2018 also yielded the second
highest ROI.  And lastly, after refactoring the VBA script, the time it took to run each script dropped to less than
1/6 of the time as the original script.  Those run times are shown below in the imbedded images.

![alt text](https://github.com/jseverin1984/stock-analysis/blob/master/resources/VBA_Challenge_2017.png "runtime for 2017")

![alt text](https://github.com/jseverin1984/stock-analysis/blob/master/resources/VBA_Challenge_2018.png "runtime for 2018")


## Summary

- Some advantages and disadvantages of refactoring code in general.

	In general, refactoring any code written if done right, will speed up the how quickly the code can run. It should
	minimize the memory needed to run the code. The overall flow and look to the code should be smoother and easier
	to understand. A disadvantage would be you are re-tooling something that is not broken and already works. Also, more
	person hours are spent on a task that could better be used on something else.

- Advantages and disadvantages when comparing the original and refactored VBA script.

	After completing and running both scripts, the refactored script ran faster and had better comments to help someone
	reading the code understand what was being accomplished during each step. Also, with the refactoring, it will allow new data
	to be input into the workbook and immediately be able to be ran through the code without any changes.  As for a disadvantage,
	 you are spending hours essentially trying to fix something that is not broken when those hours could be used on something 
	else.  There is also the risk of breaking your already functioning code and having difficulties restoring it to its working order.  