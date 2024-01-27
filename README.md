# Krippendorff-alpha-for-ordinal-nominal-and-interval-data
Current programs for calculating Krippendorff's alpha only seems to support nominal datas. However, for ordinal and interval datas, different approaches should be applied. To be specific, different Difference Functions should be chosen. Here is a function for computing Krippendorff's alpha that can accommodate three of the most common data types: nominal, interval, and ordinal data.

To compute Krippendorff's alpha, just use the krippendorff_alpha() function.

The algorism is built based on the article "Computing Krippendorff's Alpha-Reliability" by Klaus Krippendorff. For further detail, please check this article:
https://www.asc.upenn.edu/sites/default/files/2021-03/Computing%20Krippendorff%27s%20Alpha-Reliability.pdf
