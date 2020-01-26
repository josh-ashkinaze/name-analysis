# Name-Analysis

In this analysis, I took a look at baby names going back to the 1800s. This project involved a lot of data wrangling, and some clever metric-making! (What does it mean for a year to have unique names?)

[See my blog for a writeup](https://www.joshash.space/data-science/names-analysis) 


## My Questions

* Have have features of names changed over time? 

* Are names becoming more or less unique?

* How do names change during economic growth or contraction periods?


## My Findings

* Name complexity (length, vowels, syllables) is camel-shaped. There are two humps--one at around 1920, and a higher one around 2000. Interestingly, both periods preceded recessions. 

* Uniqueness decreased in the mid 20th century, but then increased after around 1960. Name uniqueness has been increasing ever since. From 1880 to 2018, the odds of 2 random Americans sharing the same name went from 1% to a tenth of 1%.

* During economic contractions, names become less unique. 

## Files

* `name_data.zip` is a zip file containing: text files of names at the yearly level, a script to merge these files into one file (`merge_files.py`), and the merged file (`merged.csv`) 

* `name-analysis.ipynb` is my python notebook of analysis



```
         .        .  
  * _  __|_  _. __|_ 
  |(_)_) [ )(_]_) [ )
._|

```
