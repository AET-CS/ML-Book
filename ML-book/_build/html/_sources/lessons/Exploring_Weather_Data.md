
# Exploring Weather Data

The file [weather-daylight.csv](../data/weather-daylight.csv) contains observational weather data for Leesburg, VA. We want to
analyze the hypothesis "the fall of 2023 had more cloudy and rainy weekends than normal."
As a class, let's look at the data and talk about our ideas for processing it. Open this file in Microsoft Excel, or something like it.

What questions do you have? What pre-processing is relevant?
What types of calculations would support or refute the claim? Do you know how to make
those calculations in Python or another language or tool?

## Look at the data
The first thing to do is just look at the data set. What do you see? Here are some questions you should ask.
- How many rows, how many columns?
- Is the data rectangular (are all rows the same length?)
- What types of data? (Numerical, categorical?)
- What domain of data (numerical: min and max, precision, mean, variance; categorical: number of categories)
- Any missing data?
- Is the file clean (read/write errors? paragraphs of text before or after? anything else weird?)
- Find meaning: What do the columns are rows mean? Are there headers? Are they defined?
- What is the source? Is this data reliable?
- Here's a list of the names of the [Weather columns](../data/weather-columns.md)

## Analyse the data
- What question are you asking?
- What does the data say about the question?
- Repeat the last 2 steps as needed!

## Jupyter Notebook
- Follow this link to a [jupyter notebook](notebooks/Weather.ipynb)

## Homework
- Open the jupyter notebook above from class on mybinder.org (or you can run it locally as `jupyter-lab` in your `ml` folder on WSL. Make sure to copy the notebook to your `ml` folder first.
- Devise a different way to analyse the question about the weather in Leesburg and try to analyse it using pandas. What conclusion can you draw?
- Make some interesting plots from this dataset. You will need to read up on plotting in dataframes using pandas and possibly some things about pyplot.
- Consider the [London Weather dataset](../../data/london_weather.csv). Investigate the question "Has the weather in London gotten worse in the last 50 years?" Analyse the data and make a claim that you can support. Source for dataset: [https://www.kaggle.com/datasets/emmanuelfwerr/london-weather-data](https://www.kaggle.com/datasets/emmanuelfwerr/london-weather-data), which retrieved the data from [https://www.ecad.eu/dailydata/index.php](https://www.ecad.eu/dailydata/index.php).
