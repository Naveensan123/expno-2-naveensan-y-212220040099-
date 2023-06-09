# expno-2-naveensan-y-212220040099-
Ex02-Outlier
You are given bhp.csv which contains property prices in the city of banglore, India. You need to examine price_per_sqft column and do following,

(1) Remove outliers using IQR

(2) After removing outliers in step 1, you get a new dataframe.

(3) use zscore of 3 to remove outliers. This is quite similar to IQR and you will get exact same result

(4) for the data set height_weight.csv find the following

(i) Using IQR detect weight outliers and print them

(ii) Using IQR, detect height outliers and print them

Ex-02_DS_Outlier_Detection_and_Removal

AIM

To detect and remove the outliers in the given data set and save the final data.

Explanation

Outlier is a data object that deviates significantly from the rest of the data objects and behaves in a different manner. They can be caused by measurement or execution errors. The analysis of outlier data is referred to as outlier analysis or outlier mining. The box plot is a useful graphical display for describing the behavior of the data in the middle as well as at the ends of the distributions. The box plot uses the median and the lower and upper quartiles (defined as the 25th and 75th percentiles). If the lower quartile is Q1 and the upper quartile is Q3, then the difference (Q3 - Q1) is called the interquartile range or IQ.

ALGORITHM

STEP 1

Import the required packages(pandas,numpy,scipy)

STEP 2

Read the given csv file

STEP 3

Convert the file into a dataframe and get information of the data.

STEP 4

Remove the non numerical data columns using drop() method.

STEP 5

Detect the outliers in the data set using z scores method.

STEP 6

Remove the outliers by z scores and list manupilation or by using Interquartile Range(IQR)

STEP 7

Check if the outliers are removed from data set using graphical methods.

STEP 8

Save the final data set into the file

OUTPUT

https://colab.research.google.com/drive/1wxmmu0TG9M3g3HmgfA3RoxzUZdCQEdck?usp=sharing

RESULT

Thus the required output is displayed.



