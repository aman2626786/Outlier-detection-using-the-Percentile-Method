# Outlier detection using the Percentile Method 

Outlier detection using the percentile method is a statistical technique used to identify data points that significantly differ from the rest of the data in a dataset. Here's how it works:

**Calculate Percentiles:** Percentiles divide the dataset into 100 equal parts. For instance, the 25th percentile (Q1) is the value below which 25% of the data lies, and the 75th percentile (Q3) is the value below which 75% of the data lies.

**Interquartile Range (IQR):** Calculate the IQR, which is the difference between the 75th percentile (Q3) and the 25th percentile (Q1). Mathematically, IQR = Q3 - Q1.

**Define Boundaries:** Determine the boundaries for outliers. Typically, data points below Q1 - 1.5 * IQR or above Q3 + 1.5 * IQR are considered outliers. These boundaries can be adjusted depending on the desired sensitivity.

**Identify Outliers:** Data points that fall outside the defined boundaries are considered outliers.
