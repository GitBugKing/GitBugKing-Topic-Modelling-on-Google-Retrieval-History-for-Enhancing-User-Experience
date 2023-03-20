# GitBugKing-Topic-Modelling-on-Google-Retrieval-History-for-Enhancing-User-Experience

Author: Zheng Liu  
Date: 07/2022 - 09/2022  
Summary: 2022 MSc graduation project in UoN which is a research about NLP, specially on Topic Modelling.

This is the repository for the MSc project researched by Zheng Liu and supervised by Kai Xu in summer 2022. File structure is described as followed:  

0. Instuction note (this file, aka, readme.md);  
1. Document (such as literature review and final report);  
2. Code (versioning)

Project Introduction:  
The whole project is a Sensemaking project which is aming to develop a Google Chrome extension for enhancing user retrieval experience. The extension will capture the links user explored and provide service like Visualization, Analysis and Recommendation depending on links. The research of whole Sensemaking project could be seperated as front-end and back-end parts. The members took responsiblity for front-end researched different ways for visualizing user exploration in real-time after opening the extension. The importance of my back-end technology in this Sensemaking project is analysing the exploration history from the moment user opening the extension until stopping exploration, the user tick the button for sending the order of searching history analysis. In the future, after accumulating the analysis results for a period of time, the links are labeled, then relevant recommendations can be made from specific Google resources.

Tech Details:
First of all, getting links from Chrome browser history database file and writting all in a csv file that contain the browser history on
    the name of browsers the program detects.

The project developed on conda kernel - Python 3.9.16 and all dependencies are following.

| pacakges | version | use |
| ----  | ----  | ---- |
| browserhistory | 0.1.2 | extract browser history from a user's local computer and write the data to csv files. |
| sys | 5.9.4 | manipulate different parts of the Python runtime environment. |
| sqlite3 | 3.40.1 | integrate the SQLite database with Python. |
| csv | built-in | implements classes to read and write tabular data in CSV format. |
| os | built-in | interacting with the operating system. |
| pandas | 1.24.2 | working with relational or labeled data easily and intuitively. |
| warnings | built-in | Warnings provided situations that aren’t necessarily exceptions. |
| requests | 2.28.2 | Requests allows you to send HTTP/1.1 requests extremely easily. |
| BeautifulSoup | 4.11.2 | scrape information from web pages. |
| lxml | 4.9.2 | easy handling of XML and HTML files, and can also be used for web scraping. |
| urllib3 | 1.26.15 | urllib3 is a powerful, user-friendly HTTP client for Python. |
| re | built-in | regular expression matching operations. |
| gensim | 4.3.1 | Python library for topic modelling, document indexing and similarity retrieval with large corpora. |
| spacy | 3.5.1 | advanced natural language processing. |
| matplotlib | 3.7.1 | creating static, animated, and interactive visualizations. |  

