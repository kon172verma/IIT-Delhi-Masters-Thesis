# Towards Building a District Development Model for India
- <b>IIT Delhi Masters Thesis.</b>
- <b>Konark Verma, Jasbir Singh</b>
- Under the guidance of <b>Dr. Aaditeshwar Seth</b>, Professor at CSE Department, IIT Delhi.

## The Big Picture:
Using the Census, Satellite and Media Data, can we built a model, that could explain and analyse the socio-economic development for various districts of India.

## Overview:
Since, this is quite big and multi dimensional project, a team of students have been working on multiple threads simultaneously. These include:
- Deep and rigrous analysis of the census data
- Combining census data with day-time satellite data to predict the change in number of socio-economic variables for each district
- Using satellite data to understand and predict the built-up non-built-up areas in a district
- Using mass media and social media data to explain and analyse the development of various Indian districts.

## Our thread:
The thread we are working on is "Using mass media and social media data to explain and analyse the development of various Indian districts". Highlights of the work done so far, are as follows:
- <b>Articles Collection : </b>Based on the industrial sectors (according to the 6th economic census), Mass Media articles have been collected for each district from 7 news paper sources.
- <b>Location Resolution : </b>Used the census data for all the states and districts, to help resolve the articles to their respective locations.
- <b>Sentiment Analysis : </b>Used Senti-strength tool for performing the sentiment analysis of the articles.
- <b>Keywords extraction : Trying to extract the explanatory keywords which help us distinguish, how a district is different from another district. This has been done using :</b>
  - Rake, Tf-Idf
  - Doc-2-Vec
  - Doc-tag-2-Vec
