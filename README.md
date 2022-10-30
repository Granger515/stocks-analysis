#Week Two Challenge: A Multi-Year Analysis of Changes in Stock Prices

##Project Overview

The project used two large datasets to conduct analyses of year-to-year stock price changes in twelve stocks. Skills used included the ability to identify length of datasets based on the length of columns in the dataset, for loops, if-then statements, conducting analyses using each variable, conducting analyses using arrays, creation of buttons, displaying data, clearing data displays, formatting data, and tracking time for the calculation to complete. The analyses required identifying a stock based on its ticker code and locating the first day selling price. It then required locating the last selling price for the stock The difference was calculated along with the percent changed. Changes were displayed in a separate worksheet and formatted for easier interpretation. A means of the user selecting which dataset, by selecting a year associated with a specific worksheet, was created.

##Summary

###Stock Price Changes

As shown below stock prices generally improved in 2017 but decreased in 2018. This would not be enough data to make a recommendation on whether this is a good investment option. However, the existing code does allow for further analyses to be conducted of these and other stocks. Other stocks could be added to the existing year worksheets in the same format and the code would allow for similar analyses. Additional years of data could also be analyzed as long as the data was added in the same format and each year’s worksheet was labeled using that year. This allows for more utility of the scripts than just using it for the initial datasets.

![All Stocks 2017](https://user-images.githubusercontent.com/114311015/198860239-c2b13c50-2cf2-43d4-a570-509dff0663c0.png)

![All Stocks 2018](https://user-images.githubusercontent.com/114311015/198860244-52a4ea32-ca9a-47d4-9fcd-15f5b07100a5.png)

###Time for Analyses and Refactoring the Code

As shown below the time for analyses to be conducted were also captured. In both cases the use of arrays over analyzing each variable independently increased the speed of the analysis. This would indicate that refactoring the code to use arrays is a more efficient process. While it may not seem meaningful that a fraction of a second was gained the difference would likely increase dramatically as the data set size increased. It is also more space efficient to refractor the code for analysis by array as opposed to each variable being analyzed individually. This would save time in coding. Finally, the second approach is more likely to ensure that the analyses were done consistently. These advantages apply both to this exercise and to projects in general.

###2017 Time by Individual Variable

![VBA_Challenge_2017Old](https://user-images.githubusercontent.com/114311015/198860377-7e6bf46f-3808-4ed1-85c3-24655c09615b.png)

###2017 Time by Array

![VBA_Challenge_2017](https://user-images.githubusercontent.com/114311015/198860389-d94d5850-a9bf-4104-8446-fe95ef161d44.png)

###2018 Time by Individual Variable

![VBA_Challenge_2018Old](https://user-images.githubusercontent.com/114311015/198860397-f5635f70-823e-4831-a10c-9021a5be922b.png)

###2018 Time by Array

![VBA_Challenge_2018](https://user-images.githubusercontent.com/114311015/198860402-8b05c654-bd76-4e67-82e8-6850c897f4b5.png)

