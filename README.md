# Week 8 workshop: Edinburgh cycle hire data

Edinburgh has a bike hire scheme, where you can rent a bike from one station to another. The company which runs the scheme publishes anonymised data every month, containing all information about the bike trips people have made that month.

All available data files (since the scheme started in September 2018) are available [**here**](https://edinburghcyclehire.com/open-data/historical), as well as a description of the data. It is published under the [Open Government License (OGL)](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

The data file for October 2020 is already in the repo (`10.csv`), but you can download more data from [here](https://edinburghcyclehire.com/open-data/historical) if you want to look at other times -- for instance, if you want to have a look at changes with seasons, with the Covid-19 lockdown (which started mid-March 2020 here), etc...

## Task: make sense of the data!

Your task is to read the CSV file into a pandas dataframe, and to find interesting things in it. You can start a new .py script or a Jupyter notebook. Here are some suggestions:

- What is the average journey time and distance of bike trips on weekdays? What about weekends?
- How many stations appear in the dataset? Which were the most common starting stations? Think about how to display/plot the results of your analysis.
- What was the most common time(s) of day for journeys to be undertaken?
- Can you visualise which stations were used mostly for shorter trips and which one for longer trips?
- Can you compare the statistics of different months in summer? Is there any remarkable difference between them? (Do this with 2019 data!)

You could use pandas to extract different parts of the data from the dataframe, matplotlib or seaborn to make some plots, SciPy for statistics...

### Useful documentation links

- [pandas documentation](https://pandas.pydata.org/docs/user_guide/index.html)
- [SciPy documentation](https://docs.scipy.org/doc/scipy-1.5.4/reference/index.html)
- [matplotlib example gallery](https://matplotlib.org/gallery/index.html#)
- [seaborn example gallery](https://seaborn.pydata.org/examples/index.html)
- [pandas: timestamps](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Timestamp.html)

You can also look at the Week 7 and Week 8 tutorial notebooks for examples.
