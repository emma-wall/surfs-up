# Surfs-Up

## Overview
This analysis uses jupyter notebooks via Python to read and analyze Hawaii weather data from an sqlite file. Specifically, I wanted to look at the data from June and December to see if a Surf and Ice Cream shop is viable all year long. 

## Results 

![Screen Shot 2021-06-20 at 9 42 33 AM](https://user-images.githubusercontent.com/80648379/122683107-36a0b480-d1cb-11eb-9a25-f68877241c64.png) ![Screen Shot 2021-06-20 at 1 30 18 PM](https://user-images.githubusercontent.com/80648379/122683200-b62e8380-d1cb-11eb-8d76-4c245c7dac3a.png)



- Average Temperatures 
    - The December average temp is only about 4 degrees cooler than in June with the Dec average temp at 71° and June at 75°.
- Standard Deviation
    - The standard deviation is greater in the Decemeber data than the June data, which means that the December temperatures are more spread out. 
- Interquartile Range
    - Although the min in December is 56°, it appears to be an outlier from the below box and would not have a significant affect on the business. The middle 50% of the data lies between 69° and 74° in December. 
    ![Screen Shot 2021-06-20 at 1 39 37 PM](https://user-images.githubusercontent.com/80648379/122683491-82545d80-d1cd-11eb-832f-d086afb516a7.png)


## Summary 
The average temperatures in June are only slightly higher than in December, therefore I do not think it would impact the business that much. I ran queries to filter the precipitation in both June and December. 

![Screen Shot 2021-06-20 at 1 39 49 PM](https://user-images.githubusercontent.com/80648379/122683430-1a9e1280-d1cd-11eb-85b3-463d8a95d0cb.png) ![Screen Shot 2021-06-20 at 1 41 49 PM](https://user-images.githubusercontent.com/80648379/122683472-6486f880-d1cd-11eb-87de-0a39486c8360.png)

The average precipitation 0.14 for June and 0.22 for December. Looking at the interquartile stats, it does not look like rainfall in Decemeber differs that much from the rainfall in June and would not have a negative impact on the Surf and Ice Cream Shop
