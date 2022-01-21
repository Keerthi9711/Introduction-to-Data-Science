# Introduction-to-Data-Science
Mathematical Preliminaries and Statistical concepts needed for Data Science


Objective of this project is to perform Analysis of variance over a data set, with a wide variety of samples to identify the variance in the mean of all samples across all features in the given data set is equal, or the difference in the average of the samples is so high that it resembles unlikely to form the chance alone.

Exploratory Data Analysis (EDA) is performed over the data set before calculating the mean squares between the groups to eliminate the noise in the data provided. Box plots are then plotted for each group to visualize the mean and its variation across the different groups. ANOVA analysis is then conducted over the refined data. F-test and its corresponding p-value are determined accordingly to check the null hypothesis. If the mean across all groups is not equal (i.e. Null hypothesis is rejected), then a T-test is performed to carry out the comparison of the means of the two samples at the same time to identify the sample with a different mean. Finally, Normality conditions were assessed by QQ plot, Shapiro test, and histogram to see whether the data within each group is normal or not and homogeneity is gauged by Bartlett's and Levene's test to see whether the variance is the data within each group is same or not.
