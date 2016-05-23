Developing Data Products Project
=======================================================
author: Vikas Arora
date: Mon May 23 22:58:57 2016
transition: rotate
font-family: 'Helvetica'

Introduction
========================================================
type: sub-section

This presentation is part of Developing Data Products Project having a peer assignment. There are two parts to it.
- Create a Shiny application and deploy it on Rstudio.
- Use Slidify or Rstudio Presenter for a pitch presentation.
We are addressing the second part of the course project using Rstudio Presenter.

The app developed for the first part of the assignment is avalilable at: https://vikasarora1980.shinyapps.io/Shiny/.
The presentation is available at:
http://rpubs.com/vikasarora1980/DataProductsPitchPresentation.
The code is present at
https://github.com/vikasarora1980/dataproducts/.


CHOOSE THE CAR HAVING BEST MILEAGE
========================================================
type: prompt

This app helps you to choose a car having best mileage using mtcars dataset in 2 steps.

Step 1: Select the distance of your trip and the price of gasoline in your region. These information will be used to calculate the Gasoline Expenditure for each car in the dataset. Then, you can enter the maximum amount of money you want to spend on gasoline, and the table shows only the cars that have Miles per Gallon (mpg) that can go below this value.

Step 2: Choose some characteristics of the cars that you desire: Cylinders, Displacement, Horse Power and Transmission. The table will show only the cars with the filters selected.

MTCARS DATASET
========================================================
type: prompt
incremental: true

The data used in the app comes from the Motor Trend Car Road Tests (mtcars) dataset. The data was extracted from the 1974 Motor Trend US magazine, and comprises fuel consumption and 10 aspects of automobile design and performance for 32 automobiles (1973-74 models).We can look to some characteristics of the data:


```
                   mpg cyl disp  hp drat    wt  qsec vs am gear carb
Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

MTCARS PLOT
========================================================
type: prompt

Here we can see the relationship between three variables: miles per gallon (mpg), displacement (disp) and weight (wt).

![plot of chunk unnamed-chunk-2](DataProdAssignment-figure/unnamed-chunk-2-1.png)
