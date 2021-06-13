Below is a snippet of code that explain a way in which we could wriite a python data frame into the different worksheet of the same google sheet document.

I have taken an example in which we have a main sheet which contain text data. The data has three columns, we are splitting the data into different sheets, based on the value of particular column.

Audio          Action          Intensity
--------      --------        ----------
.....          ....             .......
...            ....             .......
....           ....             .......

We will try to write the all the rows of records corresponding to a distinct value in Action column to a seperate worksheet. i.e, all the records corresponding to STOP action value would be moved to a seperate worksheet named STOP, and similarly for different action values.



