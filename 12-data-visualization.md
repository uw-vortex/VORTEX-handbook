# Data Visualization

## Graphing software
As part of our decision to use R for open science practices, we will be making a concerted effort to use R for all conference and publication plots. Starting R can be daunting for those new to coding, but we will try to provide as many resources as possible to get you started. On this page, you will find standard code sections for formatting graphs to keep visualization consistent across the lab.

## General theme
For publication quality graphs, we will use these theme settings based on the theme_classic() preset. This allows:
* X- and Y-axis solid black lines
* Larger text font and spaced out axis titles
* Larger margins around the plot
* Bottom oriented legend (although this will be moved within the plot borders, depending on the data)
* Absence of gridlines, plot borders, titles, or captions


```r
theme_classic()+
theme(
  text = element_text(size = 16),
  plot.margin = margin(t = 1, r = 1, b = 1, l = 1, "cm"),
  legend.position = "bottom",
  axis.text.x = element_text(vjust = 0), #Moves x axis labels down
  axis.text.y = element_text(hjust = 0), #Moves y axis labels left
  axis.title.x = element_text(vjust = -2), #Moves x axis title down
  axis.title.y = element_text(vjust = 2) #Moves y axis title left
)
```
