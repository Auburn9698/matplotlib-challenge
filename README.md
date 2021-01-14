# matplotlib-challenge
matplotlib-challenge
# Matplotlib Homework - The Power of Plots

## Background
What good is data without a good plot to tell the story?
So, let's take what you've learned about Python Matplotlib and apply it to a real-world situation and dataset:

![Mouse Image](https://github.com/Auburn9698/matplotlib-challenge/blob/main/data/Mice%20CPR.jpg)

 Pymaceuticals Inc., a burgeoning pharmaceutical company based out of San Diego, specializes in anti-cancer pharmaceuticals. In its most recent efforts, it began screening for potential treatments for squamous cell carcinoma (SCC), a commonly occurring form of skin cancer.
In this study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals' drug of interest, Capomulin, versus the other treatment regimens. Y

Summary Informtion is below:

* We checked the data for a mouse ID with duplicate time points and removed data associated with that mouse ID.


* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

![Summary Image](https://github.com/Auburn9698/matplotlib-challenge/blob/main/Images/Summary.jpg)


* Generated a bar plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows  the number of total mice for each treatment regimen throughout the course of the study.

![Timepoint Image](https://github.com/Auburn9698/matplotlib-challenge/blob/main/Images/Timepoints.png)


* Generated a pie plot using both Pandas's DataFrame.plot() and Matplotlib's pyplot that shows the distribution of female or male mice in the study.
![Gender Image](https://github.com/Auburn9698/matplotlib-challenge/blob/main/Images/Gender.png)



* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculate the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

 - Capomulin shows no outliers.
 -  Ramicane shows no outliers.
 -  Infubinol has outliers: 31    36.321346
 - Ceftamin shows no outliers.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

![Boxplots image](https://github.com/Auburn9698/matplotlib-challenge/blob/main/Images/Boxplots.png)


* Selected a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

![Mouse 185 Image](https://github.com/Auburn9698/matplotlib-challenge/blob/main/Images/Mouse185.png)


* Scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen with regression model on top of second chart.

![Scatter plots](https://github.com/Auburn9698/matplotlib-challenge/blob/main/Images/Charts.png)

Obersvations:
* Capomulin and Ramicane seem to be the most effective treatments in terms of tumor volume, showing the greatest reduction in tumor volume over time.

* Mouse weight and tumor volume seeem to be positively related on Capomulin, with a correlation coefficient of 0.84. The heavier mice tend to have greater tumor volumes.

* The number of timepoints for Capomulin and Ramicane also seem to have a positive effect on number of surviving mice. Given similar numbers of mice treated on each drug, there are noticeably more timepoints for those two, indicating more mice making it through the end of the study.
