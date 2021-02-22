# AnaAGG-P4_Api-sentiment-project

![portada](https://www.juliedesk.com/wp-content/uploads/2017/04/Featured-quotes-focus.png)

The main objectives of this project are:

        1. Create an API 
        3. Perform a sentiment analysis of our API quotes


# Collection Structure

![esquema](https://github.com/AnaAGG/P4_Api-sentiment-project/blob/main/Images/Esquema.png)


The database is made up of three collections that will receive or give the information through the API. These collections are: **Literature, Philosophy and Sciences**.

These three collections will feed into a general collection called Quote_Author collection where all the information about Author, Citation, Genre and Category is stored.

# API description

QuoteAPI is an API to collect famous quotes from different authors throughout history. This API will collect citations from different disciplines which form the basis of the API structure and therefore of the database in mongo.


## Endpoints Structure

> *"/Data"* --> to obtain all the information about authors, categories and phrases from our entire database

> */AuthorAndQuote* --> to obtain all the authors of the API

> *"/Authors/<Collection>"* --> to get all the authors contained in a given collection

> *"/Quotes/<Collection>"* --> to get all the quotes contained in a given collection

> *"/<Collection>/delete"* --> Delete a certain author and his / her quote from the givrn collections

> *"/<Collection>/new"* --> Insert a new author and his / her citation from the given collection

> *"/<Collection>/update"* --> update a new author and his / her citation from the given collection

- To insert and update information in the API it is mandatory to pass the author's name, the citation and the genre.

- To remove information from the API, it is mandatory to enter the id of the object that you want to remove.


# Libraries

[BeautifulSoup](https://pypi.org/project/beautifulsoup4/)  
[bson](https://pypi.org/project/bson/)  
[flask](https://flask.palletsprojects.com/en/1.1.x/api/)  
[json](https://docs.python.org/es/3.9/library/json.html)  
[langdetect](https://pypi.org/project/langdetect/)  
[nltk](https://www.nltk.org.htlm)  
[nltk.corpus](https://www.nltk.org/howto/corpus.html)  
[nltk.sentiment.vader](https://www.nltk.org/howto/sentiment.html)  
[nltk.tokenize](https://www.nltk.org/_modules/nltk/tokenize.html)  
[pandas](https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)  
[pymongo](https://pypi.org/project/pymongo/)  
[re](https://docs.python.org/3/library/re.html)  
[requests](https://pypi.org/project/requests/)  
[seaborn](https://seaborn.pydata.org/introduction.html)  
[spacy](https://spacy.io/usage/)  
[textblob](https://textblob.readthedocs.io/en/dev/)  








