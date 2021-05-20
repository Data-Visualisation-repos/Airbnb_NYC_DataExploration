
# Airbnb NYC Data Exploration Project

The goal of this exercise is to explore NYC data, clean it up, and model it to build data vizualizations to get a few key insights about the data. I ahve explained the results on my blog on medium. Click link to access it - https://rekula-d.medium.com/exploratory-data-analysis-of-airbnb-nyc-ed1998da1ee4

## Functionality
As I go through this task, I try to answer 3 specific questions
1. Which location has the highest number of listings
2. What room types are most common and their avg price in each neighbourhood
3. What are the common words used to describe the listings

## Scope
This project was created to explore data viz libraries in python. I have limited myself to NYC data.

I have used the following sources as a guide to build this project

## Output
1. Boroughs, Neighbourhoods and Locations where most listings are located
   + Most Airbnb listings are located in Manhattana and in parts of Brooklyn closer to Manhattan.

2. Common listings by room type and their avg price by borough
   + The most common roomtype is an Entire home/apt, also the most expensive. The avg prices in Manhattan are greater than rest of the Boroughs

3. Commonly used words to describe the listings.
   + Brooklyn, Manhattan, Private, Heart, Cozy are a few words used commonly to describe the listings
   + Private, spacious, east, beautiful, large are the top 5 adjectives used to describe the listings

Besides the above, I also tried to answer most commonly reviewed listings and hosts with the most number of listings

## Prerequisites
1. import the following libraries using pip
  + numpy
  + pandas
  + matplotlib
  + seaborn
  + folium
  + nltk
 
2. I have used python 3.7.4
I have the above libraries and python installed in an Anaconda environment.

## Installation
Fork this repository under your own control, then clone or download the resulting repository onto your computer. Then navigate there from the command line using the command line below:

```sh
cd <Your Path>/RESTAURANT-ANALYSIS-PY
```

> NOTE: subsequent usage and testing commands assume you are running them from the repository's root directory.

Use Anaconda to create and activate a new virtual environment, perhaps called "dataviz":

```sh
conda create -n dataviz python=3.7.3 # (first time only)
conda activate yelp
```

From inside the virtual environment, install package dependencies by running the below command.

```sh
pip install -r requirements.txt
```

## Sources
I would like to thanks the authors of the below blog posts.
1. https://towardsdatascience.com/an-extensive-guide-to-exploratory-data-analysis-ddd99a03199e
2. https://towardsdatascience.com/data-exploration-on-airbnb-singapore-01-40698c54cac3

## License 
LICENSE.md

## Contact
Any feedback can be emailed to rekula.d@gmail.com

