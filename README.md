# Information_Retrieval-Simple_Search_Engine
## UCI CS 121 Information Retrieval Project(Assignment3)

### Required library:

	NLTK - pip install nltk
	BeautifulSoup4 - pip install beautifulsoup4
	Simhash - pip install simhash
	Flask - pip install Flask
  
### How to run the code that creates the index?

	1. Open Indexer.py
	2. Change the root(the address of the DEV folder) and storeRoot(the address of where you want your index files be placed)  under "if __name__ == '__main__':"
	3. Run the program
	4. Wait until the program ends to see the index files (a folder named "TEST" containing all the indexes classified according to their first initial character)

### How to start the search interface (text interface)?

	1. Open Searcher.py
	2. Change the root (the address of where your index files be placed) under "if __name__ == '__main__':"
	3. Run the program
	4. After you start Searcher.py, each time you want to search, type in the query and hit enter
	5. To exit the program, simply hit enter	
