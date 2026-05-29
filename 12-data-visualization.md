# Data Visualization

## Graphing software
As part of our decision to use R for open science practices, we will be making a concerted effort to use R for all conference and publication plots. Starting R can be daunting for those new to coding, but we will try to provide as many resources as possible to get you started. On this page, you will find standard code sections for formatting graphs to keep visualization consistent across the lab.

## Inspiration
If you are looking for a fresh take on your plots, check out [The R Graph Gallery](https://r-graph-gallery.com/), which hosts many different types of R plots and sample code to work from. We will use this website as a training tool for the lab to learn how to update your aesthetics for publications and presentations.

## General theme
**We are always looking for a fresh look! Each term, I challenge lab members to work on new templates for publications, presentation, and knowledge translation activities. The collective 'best' templates will be updated here.**

We are currently working on updating a lab R package for Jason-approved plotting aesthetics. This will eventually be available to install to your personal computers. Below is the main theme for publications:

```
theme_lab <- function(base_size = 12, base_family = "sans") {
  theme_classic(base_size = base_size, base_family = base_family) +
    theme(
      axis.line = element_line(linewidth = 0.4, colour = "black"),
      axis.ticks = element_line(linewidth = 0.3),

      axis.text = element_text(size = rel(0.9), colour = "black"),
      axis.title = element_text(size = rel(1.0)),

      plot.title = element_blank(),

      legend.position = "bottom",
      legend.title = element_blank(),
      legend.text = element_text(size = rel(0.9)),
      legend.key.height = unit(0.8, "lines"),
      legend.spacing.x = unit(0.5, "lines"),
      legend.box.spacing = unit(0.5, "lines"),

      panel.grid = element_blank(),

      strip.background = element_blank(),
      strip.text = element_text(size = rel(0.95), face = "plain"),

      panel.spacing = unit(1, "lines")
    )
}
```
