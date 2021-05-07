# Creating Zoning Maps Using Python & Pandas
By following this tutorial, you’ll learn to navigate geographic shapefiles in a Jupyter Notebook (we'll be using Colab). You will upload data from DC’s open data portal, and then concatenate datasets and conduct some basic analysis. Finally, you'll create a basic map, and create a new `.shp` file that can be used with ESRI products... or can be uploaded to a service like [Carto](https://www.carto.com/) to create the online map you see below! Check out a live version of [my final map here](https://shadrock.carto.com/builder/df4c5d9f-1c1e-4df4-bb15-42681ba14aac/embed?state=%7B%22map%22%3A%7B%22ne%22%3A%5B38.838460360929645%2C-77.21660658717157%5D%2C%22sw%22%3A%5B39.03127554305828%2C-76.8502812087536%5D%2C%22center%22%3A%5B38.93493348047009%2C-77.03344389796258%5D%2C%22zoom%22%3A12%7D%7D).  
![Shadrock's cool map](images/Carto_ouput.png)

### To complete this assignment you will need:
- A Google account. We'll be using Colab, but also space in your Google Drive: this will be nice example of hosting a small data science project with your own services.
- Data downloaded from [OpenData D.C.](https://opendata.dc.gov/). If, for some reason you can't access the site or download the data, there is a [data folder in this repo](data) that contains archived data you could use. That being said, I want you to use the most recent data you can get!
- A free student account on Carto. You can _only_ get one of these by authenticating with your [Github Student Developer pack](https://education.github.com/pack) (pretty nifty, eh?). [Go here for details and links](https://carto.com/help/getting-started/student-accounts/): the process shouldn't take long. Note that a normal, free, Github account will not work!

Note that, in the tutorial below, I have included screenshots of what your output should look like. You will not always have the exact same output (especially because you're using the most recent data) but they should give you a sense of what your code should produce. In some cases, your code will simply produce a notifcation that something has run, or the result of a print statement: I have not included screenshots for these.

### What you will submit:
A link to your Github repo. The repo must contain your Python code (either as script in `.py` or a notebook in `.ipynb` format). The `README` of your repo should briefly summarize the project (in your own words), show an image of your final output, *and* link to your final map in Carto. You do not need to include the input/output files (as I have here) but it might be a good idea if you want to use this repo as part of your portfolio.

## Why is this lab important?
The United States is facing a housing crisis. The cost of housing has skyrocketed and wages have not kept pace: housing instability threatens 11 million Americans. One, little understood, aspect of the housing crisis is evictions. The [Eviction Lab](https://evictionlab.org/) is studying this to try and understand the phenomenon, which is potentially even [more devestating during the current pandemic](https://www.forbes.com/sites/samchandan/2020/07/25/americas-next-housing-crisis-how-the-pandemic-is-pushing-renters-to-the-brink/#2a98d7bd1527), and which is [starkly impacted by race and income](https://www.urban.org/urban-wire/new-data-suggest-covid-19-widening-housing-disparities-race-and-income). The Eviction Lab built the *first* nationwide database of evictions only *recently*. This is amazing when you consider it: there was no data available! Remember this in any humanitarian program you are part of: if it isn't measured, it isn't managed. How can you manage something when you don't understand the scale or scope of the problem?!


In this lab, we'll use Python to gather some open data about zoning in D.C. and create a map of zoning exemptions. This would be the first step to overlaying these data with other demographic data and will answer the question:
_Can we categorize and visualize buildings that received a zoning exemption in Washington, DC?_

## Data from Open Data DC!



## Translating Maps to Tables


# Citation
This tutorial was originally created by [Nicole Janeway Bills](https://twitter.com/nicole_janeway), who provides a nice [video walkthrough on YouTube here](https://www.youtube.com/watch?v=b9G2T4CPYVM&feature=emb_logo). I've changed some of the code slightly to deal with different inputs (Open Data D.C.'s file formatting has changed since the original tutorial); added more background context on the scenario, and added the use of Carto for a final output.
