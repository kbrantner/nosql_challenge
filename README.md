# nosql_challenge

#Description

In this project I evaluated the ratings of a variety of establishments in the United Kingdom, starting with data that was saved to a json file. I imported the data to a MongoDB database called “uk_food”. Then using an instance of the Mongo Client I was able to setup the collection within the “uk_food” database for analysis by viewing documents, inserting a document, running queries, changing datatypes, and even deleted all the documents where the “LocalAuthorityName” is Dover. Once the database was cleaned I was able to analyze the data in the “NoSQL_analysis_starter” file by running a variety of queries. The final analysis used a pipeline to run the query to best answer the question. The specific questions and analysis results can be found in the code. 

#Installation

For this code to run the following dependencies are required:
from pymongo import MongoClient
from pprint import pprint
import pandas as pd

#Support

If help is needed with NoSQL coding, I recommend searching Stack Overflow for the answers to specific questions.  

#Authors and acknowledgment

This project was completed by Kelsey Brantner. I received help from Bethany Lindberg, who helped me understand how to set the “Rating Value” to “None” in the “NoSQL_setup_starter” file when the “Rating Value” was a string, in order to be able to change the datatype to integer for the “Rating Value”. 

#Resources

According to the files’ source site, “UK Food Standards (https://www.food.gov.uk/). (2022). UK food hygiene rating data API ( https://ratings.food.gov.uk/open-data/en-GB). Contains public sector information licensed under the Open Government License v3.0(https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).”

#Project status

At this time, the project is considered complete. 
