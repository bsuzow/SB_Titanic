# Ggplot2 Exercise - Titanic.R

This repository serves as a means to deliver Project 1 of the Exploratory Data Analysis utilizing the `titanic` data frame referenced in [one of the DataCamp exercises](https://campus.datacamp.com/courses/data-visualization-with-ggplot2-1/chapter-5-qplot-and-wrap-up?ex=8). The exercise guides students step-by-step to create 3 plots - a bar plot, a bar plot with panel and a dot plot with panel. 

- Plot 1 shows male and female passenger distributions by passenger class (pClass).  The passenger class 3 occupants were predominantly male. 
- Plot 2 illustrates the same type of distributions as Plot 1, but split them to two groups based on survival.  Across passenger classes, the number of female survivors exceeded that of males.  The proportions of male survivors in Classes 2 & 3 are much lower than Class 1.
- Plot 3 replaces Count with Age in a dot plot with panel reveals a few interesting points:
    * For female passengers, passenger class seems to be a dominant predictor over age.  Class 1 & 2 female passengers had high survivability across the age. 
    * Almost all younger passengers (<=10) in Classes 1 & 2 survived.
    * Almost all passengers over 40 in Class 3 did not survive. 
