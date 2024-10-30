![image link]()

#  Analysis on Film Production.
---

## Introduction

---

## Business Problem
Your company now sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office.
   
---

## Aim of the Project
The project aims to translate findings into actionable insights that the head of our company's new movie studio can use, to help decide what type of films to create. Our main goal as data scientists is to ensure the success of the company's new movie studio by offering the most appropriate business advice.

---

## Objectives

1. Evaluate the impact of release timing. 
2. To Identify the highly rated genre.
3. To analyze the performance of films in different budget ranges.
4. To identify the most produced genre by other producers.

---

### The project members include; 

 * Sarah Joshua,
 * Aurel Ochieng, 
 * Daniel Karue,
 * Levis Gichuhi, 
 * Michelle Anyango &
 * Michael Njoroge.

## Data Understanding and Analysis

### Data Source

The data for this analysis is obtained from multiple reputable sources:
* [Box Office Mojo]: Provides comprehensive box office revenue data.
* [IMDB]: A rich source of movie ratings, genres, and other detailed movie information.
* [Rotten Tomatoes]: Offers critical and audience reviews and ratings.
* [TheMovieDB]: Contains detailed movie information, including genres, ratings, and runtime.
* [The Numbers]: Provides financial data on movie budgets and grosses.

The data represents a comprehensive collection of information on films, including their financial performance, ratings, genres, and other attributes. The sample includes a diverse range of films across different genres, time periods, and budgets.

---

### Description of Data

**Production Budget:** The cost to produce a film.

**Gross Revenues:** Box office earnings, both domestic and worldwide.

**Release Date:** Timing of film release which impacts its performance.

**Genres:** Categories of films that indicate the type of content.

**Original Language:** The primary language in which the film was produced.

**Runtime Minutes:** The length of the film in minutes.

**Average Rating:** The average rating received from audiences and critics.

---

### Loading and Cleaning of Data

The activities conducted include:

 * Importing required libraries.
 
 ``` python
 import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import sqlite3
%matplotlib inline
 ```
 
 * Handling missing values.
 
   It is crucial in data processing, analysis and improving data visualization.
 
 * Removing duplicate values.

   Ensures data integrity and improves model performance.
 
 * Standardizing columns.
 
   Reduces sensitivity to outliers.
 
 * Selecting features of interest.
 
---

### Visualization

1.viz seasons bar graph by mean worldwide gross

![image link]()


2.check for correlation btn production budget and worldwide gross.

![image link]()


3.Distribution of top 10 genres.

![image link]()


4.visualization of the average rating.

![image link]()

---

### CONCLUSIONS AND RECOMMENDATIONS

####  CONCLUSIONS
1. By understanding the relationship between budget and box office performance, studios can make informed decisions about budget allocation and risk management.
2. By focusing on high-rated genres, studios can attract a wider audience and improve their chances of critical and commercial success.
3. By carefully considering release timing, studios can optimize their release calendar to maximize box office performance and minimize competition.

---

#### RECOMMENDATIONS

1. Utilize holidays and festive periods to attract a larger audience, that happens mostly during the summer
2. Focus on producing films in genres that consistently receive high ratings from critics and audiences.
3. Invest in high-budget films with strong potential for high returns, while also exploring lower-budget films with lower risk.
4. Identify popular genres that are currently in demand and consider producing films in these genres.

---

