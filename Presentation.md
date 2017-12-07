Shiny app
========================================================
author: Mladen Tukeric
date: 7.12.2017
autosize: true

Shiny App
========================================================

In this app you can check different regression models of mtcars:

- Filtered on Number of cylinders (cyl)
- Prediction of miles per gallon (mpg) based on weight (wt)
- You can select only few points on graph to calculate new regression model only on these values

Mt cars dataset
========================================================

For this app we use mtcars dataset

```r
head(mtcars)
```

```
                   mpg cyl disp  hp drat    wt  qsec vs am gear carb
Mazda RX4         21.0   6  160 110 3.90 2.620 16.46  0  1    4    4
Mazda RX4 Wag     21.0   6  160 110 3.90 2.875 17.02  0  1    4    4
Datsun 710        22.8   4  108  93 3.85 2.320 18.61  1  1    4    1
Hornet 4 Drive    21.4   6  258 110 3.08 3.215 19.44  1  0    3    1
Hornet Sportabout 18.7   8  360 175 3.15 3.440 17.02  0  0    3    2
Valiant           18.1   6  225 105 2.76 3.460 20.22  1  0    3    1
```

mpg ~ wt
========================================================

Regression model containg whole dataset w/o filtering on number of cyl would look like this:

![plot of chunk unnamed-chunk-2](Presentation-figure/unnamed-chunk-2-1.png)


Conclusion
========================================================

By using this app you can play with different values and see how different sample data will give different result.

