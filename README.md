# nosql-challenge
Module 12 Challenge

In this project we will evaluate the ratings data produced by the UK Food Standards Agency in order to help the journalists and food magazine, Eat Safe, Love, to decide where to focus future articles.

Information regarding changes to the data base and the outputs from the requested analysis can all be found in the 'nosql-challenge' GitHub Repository. This repository includes:
- 2 x Jupyter Notebooks containing database udpates and analysis:
    - NoSQL_setup_starter.ipynb
    - NoSQL_analysis_starter.ipynb
- 1 x dataset:
    - Resources/establishments.json

The project was undertaken in three parts:

- Part 1: Import dataset/create database and set up Jupyter Notebook (see 'Part 1', 'NoSQL_setup_starter.ipynb').

- Part 2: Update database as per the request from the magazine editors(see 'Part 2', 'NoSQL_setup_starter.ipynb'). Updates include:
    - Add data from new establishment to the database and enter its BusinessTypeID so as to be consistent with other establishments of the same type.
    - Remove all establishements that reside within the purvue of Dover Local Authority.
    - Upate the datatypes of all longtidue and latitude values, so as to enable geolocation search of the establishments in the database.

- Part 3: Perform exploratory analysis in order to answer specific questions posed by the magazine in order to identify locations they wish to visit and avoid (see 'Part 3', 'NoSQL_analysis_starter.ipynb'). Questions include:
    - Which establishments have a hygiene score equal to 20?
    - Which establishments in London have a RatingValue greater than or equal to 4?
    - What are the top 5 establishments with a RatingValue of '5', sorted by lowest hygiene score, nearest to "Penang Flavours"?
    - How many establishments in each Local Authority area have a hygiene score of 0?

Further information on the project:

The dataset used ('establishments.json') is in JSON format and was imported into a MongoDB/NoSQL databse through the terminal. See 'Part 1' of 'NoSQL_setup_starter.ipynb' for the line of text used to import the dataset.

All database udpates and analysis was undertaken by Oliver King