# Life Expectancy and GDP

Data Acquisition
Data Visualization
Hypothesis Testing
Summarizing Quantitative Data
Data Wrangling and Tidying
Data Manipulation with Pandas

## Goals

This project investigates if a countries GDP effect the outcome of it's populations life expectancy

We will be looking into :

* Has life expectancy increased over time in the six nations?
* Has GDP increased over time in the six nations?
* Is there a correlation between GDP and life expectancy of a country?
* What is the average life expectancy in these nations?
* What is the distribution of that life expectancy?

## Data

all_data.csv

Contains

* Country
* Year
* Life expectancy at birth (years)
* GDP

## Analysis

We are going to get an idea of the data we are looking at

First analysis is too see how many countries we will be working with

```python
print(df['Country'].unique())
```

Next we will look at the year span in the data set to determine if the data
is adequate to work with

```python
print(f"Sampling years from {df['Year'].min()} till {df['Year'].max()}")
```

The 15 years sample seems adequate to examine for recent times (millennium), however other factors may
also effect the actual results example Covid and disasters

Next we will be looking at

Has life expectancy increased over time in the six nations?

Has GDP increased over time in the six nations?

Is there a correlation between GDP and life expectancy of a country?

What is the average life expectancy in these nations?

What is the distribution of that life expectancy?
