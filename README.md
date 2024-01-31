# Matplotlib-Pymaceuticals
Module 5 Challenge

Sources I used:
    
    https://saturncloud.io/blog/python-pandas-conditionally-delete-rows/#:~:text=We%20can%20aslo%20use%20the,met%2C%20similar%20to%20boolean%20indexing.
        To drop Mouse ID g989 (Input 5)

    https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.aggregate.html
        To use aggregation method to create summary statistics (Input 8)

    https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.isin.html
        TO create DataFrame with only the values in a certin column (Input 13)

Note on Pie Charts:
    I used .unique as opposed to the .value-counts because I felt that using the 248 unique Mouse IDs to get the percentages of Males vs Females made more sense than counting all 1880 timepoints with a male/female attribute. This caused my percentages to be a little different than the example (which I am assuming used the .value-counts method).

