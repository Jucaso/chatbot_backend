# Books recommender chatbot
This is the backend side of Pepe Chatbot, a tool that is able to recommend books for you to read.
The database of books used by the developed services was created from scratch by scraping
the information from the Universidad del Valle OPAC web page (a web page offered by Universidad del Valle for consulting book availability).

This is where the necessary services for the chatbot were developed, including processing users' text inputs, 
constructing recommendation model (Average Word2Vec), and sending the best recommendations based on the
defined technique (Cosine Similarity). 

The framework used for this development was Flask. Additionally, the libraries used included SpaCy, Pandas, Sklearn, and Gensim.

It is important to note that the application is in Spanish language. Additionally, if you want to check the frontend side, here is it:
https://github.com/Jucaso/chatbot_frontend
