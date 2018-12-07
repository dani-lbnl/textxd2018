# TextXD2018
Text mining of scientific data at scale

## Questions 
1. Concrete scientific papers: what are the keywords and how are they related? What about composition and environment impact?
2. Composition of concrete over time
3. Environment aspects of concrete production

## Main Steps
1. Go to [Web of Science](http://www.webofknowledge.com/) and download 1000 TAK
  - clean up, e.g. eliminate non-English text, check which fields are more promising - full of NAs for kw 
  - deal with [stopwords](https://pythonspot.com/nltk-stop-words/) and be aware of dependencies: nltk, punkt
  - 
2. Explore word embedding models in Python with gensim 
3. Extract features produced through the word2vec model
4. Visualization the WEMs

## References
- [Caroline Le Pennec-Caldichoury's inspiring lecture](http://www.textxd.org/programs/textxd2018/)
- [Jaren Haber's amazing tutorial](https://github.com/TextXD/charters4textxd2018)
- [Geoff Bacon's foundation course](http://www.textxd.org/programs/textxd2018/)
