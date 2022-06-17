Shiny Application and Reproducible Pitch
========================================================
author: "Chenran Zhang"
date: '2022-06-17'
autosize: true

Diamond Explorers
========================================================

This Application uses default diamond data in package ggplot2. To demonstrate various capabilities from the Developing Data Products Course. The Application provides visualization about diamonds with various factors.

- Using Shiny UI Server Application.
- Including Input Widgets (Drop down lists, check boxes, and Slide Bar).
- Using Reactive function.
- Full help page (Documentation).

Shiny Application Link : https://elijahzhang.shinyapps.io/Diamond2/ 
Github Repository Link : https://github.com/elijahzhang2021/Course-Project-Shiny-Application-and-Reproducible-Pitch

The Data
========================================================
Data str


```r
library(ggplot2)
str(diamonds)
```

```
tibble [53,940 x 10] (S3: tbl_df/tbl/data.frame)
 $ carat  : num [1:53940] 0.23 0.21 0.23 0.29 0.31 0.24 0.24 0.26 0.22 0.23 ...
 $ cut    : Ord.factor w/ 5 levels "Fair"<"Good"<..: 5 4 2 4 2 3 3 3 1 3 ...
 $ color  : Ord.factor w/ 7 levels "D"<"E"<"F"<"G"<..: 2 2 2 6 7 7 6 5 2 5 ...
 $ clarity: Ord.factor w/ 8 levels "I1"<"SI2"<"SI1"<..: 2 3 5 4 2 6 7 3 4 5 ...
 $ depth  : num [1:53940] 61.5 59.8 56.9 62.4 63.3 62.8 62.3 61.9 65.1 59.4 ...
 $ table  : num [1:53940] 55 61 65 58 58 57 57 55 61 61 ...
 $ price  : int [1:53940] 326 326 327 334 335 336 336 337 337 338 ...
 $ x      : num [1:53940] 3.95 3.89 4.05 4.2 4.34 3.94 3.95 4.07 3.87 4 ...
 $ y      : num [1:53940] 3.98 3.84 4.07 4.23 4.35 3.96 3.98 4.11 3.78 4.05 ...
 $ z      : num [1:53940] 2.43 2.31 2.31 2.63 2.75 2.48 2.47 2.53 2.49 2.39 ...
```

Shiny App
========================================================
![The screenshot of Shiny App](https://user-images.githubusercontent.com/77467304/174226879-1e0de833-f00b-40f5-8ebf-f96eb7a9738d.png)
