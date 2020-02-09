This a project with intended goal of creating a fun web interface that will generate information
about a movie that you make of the name for.

PROJECT:

Movie Predictor/Maker Project

Idea: Create a web interface that allows you to input a name and get revenue , poster, and summary out. (Further expansions possible, such as input a picture and get others)

Problems so far: 
Revenue data isnt in IMDB datasets
Images arent in IMDB datasets

1. ETL Data from IMDB

2. Create Predictor for Summary 
Semantic analysis of titles, summaries
Possible with BERT (warmed)

3. Image recreator (hardest part)
model that outputs an image based on a word

4. Wrap the model in a docker container

5. Create simple Web interface
via Flask
Fast API?

6. Prettify the Web interface into a nice project

7. Go back and possibly use an actual ETL Platform to update the model regularuly
Airflow usage perhaps