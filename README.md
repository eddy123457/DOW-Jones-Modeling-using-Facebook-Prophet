![image](https://github.com/eddy123457/DOW-Jones-Modeling-using-Facebook-Prophet/assets/23302893/456df767-e537-44ab-8779-433da60bebf7)# DOW-Jones-Modeling-using-Facebook-Prophet
Using  Facebook Prophet this project shows trend data set within the years 1985-2020. In graph one we see an in-sample prediction with the final year of the data (2020). we see that the trend line established in the model shows an inaccuracy however, this is expected due to the "crash" of the markets that happened in this year. 

In Graph 2 we see the trend line set for the entirety of the graph using Plotly as the visual aid. Using the same aid for Graph 3 we set the changepoints for the set as well.

Moving to graphs 4-6 we map seasonal trends yearly, weekly, and monthly

Lastly, using these parameters we use cross-validation  
#horizon - the forecast horizon 365
#initial - the size of the initial training period 540
#period - the spacing between cutoff dates  train with 180 days


using this we can map our final graph 'Mean Percentage Error

Here we can see that we have a 5-10% percent error for predictions within 50 days and so on

