# synonym_antonym_set
  We constructed a test set for synonym and antonyms. Each line in this test set has three words: target word, antonym, and synonym. 
We obtain an target−antonym pair from the WordNet antonym list and obtain the synonym word pair target−synonym from the PPDB,
and combine the two into a test set. This dataset contains 3,387 pairs. We calculate the cosine distance between target−antonym
and target−synonym, and accuracy is judged by whether target−synonym is closer.
