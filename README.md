# Matplotlib-Pymaceuticals
## Module 5 Challenge
This challenge/assignment was using data from drug trials on mice. 

After cleaning the data I created a dataframe for Summary Statistics.

![image](https://github.com/JacqueLeeMeyer/Matplotlib-Pymaceuticals/assets/149394665/1df2ec88-ea41-443f-9954-fe42d5af9fa1)


I then created the following graphs:

### Bar graph of Total timepoints for each Drug

![image](https://github.com/JacqueLeeMeyer/Matplotlib-Pymaceuticals/assets/149394665/2299643e-2d78-47df-9c61-97e36792ff2b)
   
### Pie chart of # of Male vs Female Mice in the study

![image](https://github.com/JacqueLeeMeyer/Matplotlib-Pymaceuticals/assets/149394665/f3399ecc-7215-4f42-ba8d-08efa802eeaf)
  
### Box and Whisker plot showing any outliers for the Drugs - Capomulin, Ramicane, Infubinol, and Ceftamin

![image](https://github.com/JacqueLeeMeyer/Matplotlib-Pymaceuticals/assets/149394665/b6d470c6-d23b-4526-8596-f2ba2fd37dc9)

### Line graph of the Tumor Volume over the 40 days of Mouse y793 (Capomulin)

![image](https://github.com/JacqueLeeMeyer/Matplotlib-Pymaceuticals/assets/149394665/51f35037-2724-4b54-a1a6-833de95efdb6)
   
### Scatter plot of the Average Tumor Volume vs Weights of all mice in the Capomulin Drug Trial

![image](https://github.com/JacqueLeeMeyer/Matplotlib-Pymaceuticals/assets/149394665/a56a823c-bf8b-4015-90be-b690aa1c1ecf)
        
### Then calculated correlation and linear regression and added it to copy of the scatter plot

![image](https://github.com/JacqueLeeMeyer/Matplotlib-Pymaceuticals/assets/149394665/0a761180-f3a3-4a4e-8f65-da056c3e94d9)



### Note on Pie Charts:
I used .unique as opposed to the .value-counts because I felt that using the 248 unique Mouse IDs to get the percentages of Males vs Females made more sense than counting all 1880 timepoints with a male/female attribute. This caused my percentages to be a little different than the example (which I am assuming used the .value-counts method).

### Sources I used:
    
    https://saturncloud.io/blog/python-pandas-conditionally-delete-rows/#:~:text=We%20can%20aslo%20use%20the,met%2C%20similar%20to%20boolean%20indexing.
        To drop Mouse ID g989 (Input 5)

    https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.aggregate.html
        To use aggregation method to create summary statistics (Input 8)

    https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.isin.html
        TO create DataFrame with only the values in a certain column (Input 13)
