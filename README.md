# Descriptive Statistics with Python Project


Descriptive statistics gives us the basic summary measures about the dataset.  The summary measures are `measures of central tendency` (mean, median and mode) and `measures of dispersion and variability` (variance, standard deviation, minimum/maximum values, IQR (Interquartile Range), skewness and kurtosis). In this project, I have described these summary measures. I have used the `fortune 500` dataset from the data world website for this project.


===============================================================================


## Table of Contents

1. Introduction to descriptive statistics
2. Sample vs Population
3. Measures of central tendency
    - Mean
    - Median
    - Mode
4. Measures of dispersion
    - Variance
    - Standard deviation
    - Coefficient of variation
    - IQR (Interquartile range)
    - Skewness
    - Kurtosis   
5. Dataset description
6. Results and conclusion
7. References


===============================================================================


## 1. Introduction to Descriptive Statistics

Descriptive statistics are numbers that are used to describe and summarize the data. They are used to describe the basic features of the data under consideration. They provide simple summary measures which give an overview of the dataset. Summary measures that are commonly used to describe a data set are measures of central tendency and measures of variability or dispersion. 

Measures of central tendency include the `mean`, `median` and `mode`. These measures summarize a given data set by providing a single data point. These measures describe the center position of a distribution for a data set. We analyze the frequency of each data point in the distribution and describes it using the mean, median or mode. They provide the average of a data set. They can be either a representation of entire population or a sample of the population.

Measures of variability or dispersion include the `variance` or `standard deviation`, `coefficient of variation`,  `minimum` and `maximum` values, `IQR (Interquartile Range)`,  `skewness` and `kurtosis`. These measures help us to analyze how spread-out the distribution is for a dataset. So, they provide the shape of the data set.


===============================================================================


## 2. Sample vs Population

The measures of central tendency and measures of dispersion are used to describe the data set under consideration. The data set may be the whole population or a sample of the population. I will start the discussion with population.


### Population

-	A population is a collection of all of the items in the dataset.
-	They are usually denoted with an upper case letter N.
-	The numbers we obtain by using a population are called **parameters**.
-	Populations are hard to define and hard to observe in real life. 


### Sample

-	A sample is a subset of the population.
-	They are usually denoted with a lower case letter n.
-	The numbers we obtain by using a sample are called **statistics**.
-	A sample is much easier to gather. They are less time-consuming and cheaper. Time and resources are the main reasons we prefer   
  analysing samples rather populations.
-	They have two key characteristics - **randomness** and **representativeness**.
-	**Randomness** means a random sample is collected when each member of the sample is chosen from the population strictly by chance.
-	**Representativeness** means a representative sample is a subset of the population that accurately reflects the members of the entire 
  population.


===============================================================================


## 3. Measures of central tendency

**Central tendency** means a central value which describe a probability distribution. It may also be called a center or location of the distribution. The most common measures of central tendency are **mean**, **median** and **mode**. The most common measure of central tendency is the **mean**. For skewed distribution or when there is concern about outliers, the **median** may be preferred. So, **median** is more robust measure than the mean.


### Mean

- The most common measure of central tendency is the mean.
- Mean is also known as the simple average.
- It is denoted by greek letter µ for population and by x bar for sample.
- We can find mean of a number of elements by adding all the elements in a dataset and then dividing by the number of elements 
in the dataset.
- It is the most common measure of central tendency but it has a drawback.
- The mean is affected by the presence of outliers.
- So, mean alone is not enough for making business decisions.

The formulae for calculating population and sample mean is given in the following diagram-


![Population and Sample Mean](https://github.com/pb111/Descriptive-Statistics-Project/blob/master/Images/Population%20vs%20Sample%20Mean.png)


### Median

- Median is the number which divides the dataset into two equal halves. 
- To calculate the median, we have to arrange our dataset of n numbers in ascending order.
- The median of this dataset is the number at (n+1)/2 th position, if n is odd.
- If n is even, then the median is the average of the (n/2)th number and (n+2)/2 th number.
- Median is robust to outliers.
- So, for skewed distribution or when there is concern about outliers, the median may be preferred.


The formulae for calculating median is as follows-


![Median](https://github.com/pb111/Descriptive-Statistics-Project/blob/master/Images/Median.png)


### Mode

- Mode of a dataset is the value that occurs most often in the dataset.
- Mode is the value that has the highest frequency of occurrence in the dataset.


There is no best measure that give us the complete picture. So, these measures of central tendency (mean, median and mode) should be used together to represent the full picture. 


The mode is depicted in the following diagram-


![Mode](https://github.com/pb111/Descriptive-Statistics-Project/blob/master/Images/Mode.png)


===============================================================================


## 4. Measures of dispersion or variability

**Dispersion** is an indicator of how far away from the center, we can find the data values. The most common measures of dispersion 
are **variance**, **standard deviation** and **interquartile range (IQR)**. **Variance** is the standard measure of spread. The **standard deviation** is the square root of the variance. The **variance** and **standard deviation** are two useful measures of spread. 


### Variance

- Variance measures the dispersion of a set of data points around their mean value.
- It is the mean of the squares of the individual deviations.
- Variance gives results in the original units squared.


### Standard deviation
	
- Standard deviation is the most common used measure of variability.
- It is the square-root of the variance.
- For Normally distributed data, approximately 95% of the values lie within 2 sd of the mean. 
- Standard deviation gives results in the original units.



### Coefficient of Variation (CV)
	
- Coefficient of Variation (CV) is equal to the standard deviation divided by the mean.
- It is also known as `relative standard deviation`.




### IQR (Interquartile range)

- A third measure of spread is the **interquartile range (IQR)**.
- The IQR is calculated using the boundaries of data situated between the 1st and the 3rd quartiles. 
- The interquartile range (IQR) can be calculated as follows:-

       IQR = Q3 – Q1
       
- In the same way that the median is more robust than the mean, the IQR is a more robust measure of spread than variance and standard deviation and should therefore be preferred for small or asymmetrical distributions. 
- It is a robust measure of spread.


The IQR is depicted in the following diagram-


![IQR](https://github.com/pb111/Descriptive-Statistics-Project/blob/master/Images/IQR.png)


### Minimum and maximum values

- Minimum and maximum values are self-explanatory.
- These are the minimum and maximum values in the data set.



### Measures of shape

Now, we will take a look at measures of shape of distribution. There are two statistical measures that can tell us about the shape of the distribution. These measures are **skewness** and **kurtosis**. These measures can be used to convey information about the shape of the distribution of the dataset.




### Skewness
	
- **Skewness** is a measure of a distribution's symmetry or more precisely lack of symmetry. 
- It is used to mean the absence of symmetry from the mean of the dataset. 
- It is a characteristic of the deviation from the mean. 
- It is used to indicate the shape of the distribution of data.


#### Negative skewness
	
- Negative values for skewness indicate negative skewness. 
- In this case, the data are skewed or tail to left. 
- By skewed left, we mean that the left tail is long relative to the right tail. 
- The data values may extend further to the left but concentrated in the right. 
- So, there is a long tail and distortion is caused by extremely small values which pull the mean downward so that it is less than the median. 
- Hence, in this case we have
      **Mean < Median < Mode**


#### Zero skewness

- Zero skewness means skewness value of zero. 
- It means the dataset is symmetrical. 
- A data set is symmetrical if it looks the same to the left and right to the center point. 
- The dataset looks bell shaped or symmetrical. 
- A perfectly symmetrical data set will have a skewness of zero. 
- So, the normal distribution which is perfectly symmetrical has a skewness of 0. 
- So, in this case, we have
      **Mean = Median = Mode**


#### Positive skewness

- Positive values for skewness indicate positive skewness. 
- The dataset are skewed or tail to right. 
- By skewed right, we mean that the right tail is long relative to the left tail. 
- The data values are concentrated in the right. 
- So, there is a long tail to the right that is caused by extremely large values which pull the mean upward so that it is greater than the median. 
- So, we have
       **Mean > Median > Mode**
       
       
The skewness is depicted in the following diagram-


![Skewness](https://github.com/pb111/Descriptive-Statistics-Project/blob/master/Images/Skewness.jpeg)


#### Reference range on skewness values

The rule of thumb for skewness values are:

- If the skewness is between -0.5 and 0.5, the data are fairly symmetrical.
- If the skewness is between -1 and – 0.5 or between 0.5 and 1, the data are moderately skewed.
- If the skewness is less than -1 or greater than 1, the data are highly skewed.




### Kurtosis

- Kurtosis is the degree of peakedness of a distribution. 
- Data sets with high kurtosis tend to have a distinct peak near the mean, decline rather rapidly and have heavy tails.
- Data sets with low kurtosis tend to have a flat top near the mean rather than a sharp peak. 


#### Reference range for kurtosis

- The reference standard is a normal distribution, which has a kurtosis of 3. 
- Often, **excess kurtosis** is presented instead of kurtosis, where **excess kurtosis** is simply **kurtosis - 3**. 


Positive and negative kurtosis is depicted in the following diagram-


![Positive and negative kurtosis](https://github.com/pb111/Descriptive-Statistics-Project/blob/master/Images/Positive%20and%20negative%20kurtosis.jpg)


#### Mesokurtic curve

- A normal distribution has kurtosis exactly 3 (**excess kurtosis** exactly 0). 
- Any distribution with kurtosis ≈3 (excess ≈ 0) is called **mesokurtic**.


#### Platykurtic curve

- A distribution with kurtosis < 3 (**excess kurtosis** < 0) is called **platykurtic**. 
- As compared to a normal distribution, its central peak is lower and broader, and its tails are shorter and thinner.


#### Leptokurtic curve

- A distribution with kurtosis > 3 (**excess kurtosis** > 0) is called **leptokurtic**. 
- As compared to a normal distribution, its central peak is higher and sharper, and its tails are longer and fatter.


These curves are depicted in the following diagram-


![Lepto, Meso and Platy kurtic Curves](https://github.com/pb111/Descriptive-Statistics-Project/blob/master/Images/Lepto%2C%20Meso%20and%20Platy%20kurtic.jpg)


### Summary

So far, we have looked at the measures of central tendency of the data which include `mean`, `median` and `mode`. Also, we have taken 
a look at measures of spread of the data which consists of `variance`, `standard deviation`, `interquartile range (IQR)`, `minimum` and `maximum` values. We have also discussed `skewness` and `kurtosis` as measures of shape. These quantities can only be used for quantitative variables not for categorical variables.


===============================================================================


## 5. Dataset description

I have used the `fortune 500 dataset` for this project. I have downloaded this dataset from the data world website. This data set 
can be downloaded from the following url:–


https://data.world/alexandra/fortune-500


The data set consists of revenue and profit figures of fortune 500 companies along with their rank.


===============================================================================


## 6. Results and conclusion


1.	In this project, I describe the descriptive statistics that are used to summarize a dataset. 
2.	In particular, I have described the measures of central tendency (mean, median and mode). I have also described the measures of dispersion or variability (variance, standard deviation, coefficient of variation, minimum and maximum values, IQR) and measures of shape (skewness and kurtosis).
3.	I have demonstrated how to calculate the summary statistics with `describe()` function.
4.	I have computed the measures of central tendency-mean, median and mode for the `Revenue (in millions)`variable. I have found `mean > median > mode`. So, the distribution of `Revenue (in millions)` is positively skewed. I have plotted its distribution to confirm the same.
5.	I have computed the measures of dispersion or variability-range, variance, standard-deviation, median and IQR for the `Revenue (in millions)`variable.
6.	I have also computed the measures of shape-skewness and kurtosis for the `Revenue (in millions)`variable.
7.	I find the skewness to be 9.3267. So, it is greater than 1. Hence, we can conclude that the `Revenue (in millions)` data is highly skewed.
8.	I find the kurtosis to be 132.0456. So, it is greater than 3 and so excess kurtosis > 0. Hence, we can conclude that the `Revenue (in millions)` curve is a leptokurtic curve. As compared to a normal distribution, its central peak is higher and sharper, and its tails are longer and fatter.


===============================================================================


## 7. References

The work done in this project is inspired from the following books and websites:-

1.	Think Stats – Exploratory Data Analysis in Python by Allen B. Downey

2.	Udemy course – Statistics for Data Science

3.	https://en.wikipedia.org/wiki/Descriptive_statistics 

4.	https://www.investopedia.com/terms/d/descriptive_statistics.asp

5.	https://socialresearchmethods.net/kb/statdesc.php

6.	https://blog.usejournal.com/descriptive-statistics-with-python-6c7acb1d3671



