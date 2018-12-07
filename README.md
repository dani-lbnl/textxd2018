TextXD2018
==========

Text mining of scientific data by Alex Nascimento and Dani Ushizima

Questions
---------

1.	Scientific papers about construction materials: tokens frequency and semantics
2.	Concrete composition over time
3.	Environment aspects of concrete production

Data
----

1.	Go to Wikipedia for key words about subject, here **construction materials**
2.	Query [Web of Science](http://www.webofknowledge.com/)
	-	construction materials concrete
	-	download 387 TAK

Main Steps
----------

1.	Data clean up, e.g. eliminate non-English text, check which fields are more promising - full of NAs for kw
	-	deal with [stopwords](https://pythonspot.com/nltk-stop-words/) and be aware of dependencies: nltk, punkt -
2.	Explore word embedding models in Python with gensim
3.	Extract features produced through the word2vec model
4.	Visualization the WEMs

References
----------

-	Thanks Caroline Le Pennec-Caldichoury, Geoff Bacon and Jaren Haber [course](http://www.textxd.org/programs/textxd2018/) materials.
