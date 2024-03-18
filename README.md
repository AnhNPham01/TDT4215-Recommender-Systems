# TDT4215-Recommender-Systems


## enkel plan så langt

**Baseline** 
- finne mest populære artikkelen: på tvers av hele datasettet, men også innen en tidsperiode dag

- Ring buffer

**Collaborative filtering** 
- finne ut av det

**Content-based** 
- Bag of word, tf-idf på headlines og abstracts, BERT


## Analysis

####  Title length and abstract length distribution :heavy_check_mark:
Finished, can be pasted here


### Category distribution :heavy_check_mark:
Finished, can be pasted here

###  Click per article and through rate 
done and almost done

### Impressions over time

started but needs some revision. TODO

### Embeddings

TODO

### TF-IDF

hvis vi skal implementere TF-IDF eller noe lignende burde vi lemmatize, tokenize, fjerne stoppordord, osv. (basically det vi gjorde i IR) sånn at vi får bedre match på alle ordene