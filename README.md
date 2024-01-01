# DOW-Jones-Modeling-using-Facebook-Prophet

![newplot](https://github.com/eddy123457/DOW-Jones-Modeling-using-Facebook-Prophet/assets/23302893/a5a43fd1-e1f4-49a3-91b1-38551ac2a648)

Using  Facebook Prophet this project shows trend data set within the years 1985-2020. In graph one we see an in-sample prediction with the final year of the data (2020). we see that the trend line established in the model shows an inaccuracy however, this is expected due to the "crash" of the markets that happened in this year. 
![newplot 2](https://github.com/eddy123457/DOW-Jones-Modeling-using-Facebook-Prophet/assets/23302893/d5fbd632-42e6-4043-93af-27b2169476a2)

In Graph 2 we see the trend line set for the entirety of the graph using Plotly as the visual aid. Using the same aid for Graph 3 we set the changepoints for the set as well.

![image](https://github.com/eddy123457/DOW-Jones-Modeling-using-Facebook-Prophet/assets/23302893/b86c5afc-18af-4ef0-a2c6-48944873f4b8)

Moving to graphs 4-6 we map seasonal trends yearly, weekly, and monthly

Lastly, using these parameters we use cross-validation  
#horizon - the forecast horizon 365
#initial - the size of the initial training period 540
#period - the spacing between cutoff dates  train with 180 days


using this we can map our final graph 'Mean Percentage Error

Here we can see that we have a 5-10% percent error for predictions within 50 days and so on
![image](https://github.com/eddy123457/DOW-Jones-Modeling-using-Facebook-Prophet/assets/23302893/ba04ac65-54f4-43ef-8c21-279a76d5bd2e)

