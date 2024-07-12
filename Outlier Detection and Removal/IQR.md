# Outlier Detection using IQR (Interquartile Range)
## IQR = (75%ile value) - (25%ile value)
- #### This method is inspired by the functioning of box plot.
- #### Steps to detect and remove outlier:
- - Find the 75%ile (Q2) and 25%ile (Q1) values respectively.
  - Find the IQR.
  - Find Minimum value using the formula: Minimum = Q1 - 1.5*IQR
  - Similarly find the maximum value using: Maximum = Q3 + 1.5*IQR
  - Now we can either Trim or Cap the outlier.
