# ir_proj

A search engine project based on a corpus of 6 million+ wikipedia docs.

The main functionality is a working searcg engine which can be accessed through a url when an instance of the machine is running.

Before the app is running we make sure that there is access to all needed indices and additional mapping files which we've built ahead of time using the .pyinb files provided in this reposatory.

Once the app has started runnig and a query is sent it goes through a tokenizer to remove stopword and break up our query into searchable pieces.

The tokenized query then goes throug the wanted search function, which uses the indices provided to get the results we want.

We've used binary ranking as well as cosine smilarity formula in order to rank our results.

The search functions are provided in the search_frontend.py file, where there is further explanatoins about the functions.

Also provided, are the .py files which contain the Inverted Index classes.
