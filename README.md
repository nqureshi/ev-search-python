# Emergent Ventures Embeddings-Based Search

Emergent Ventures (https://www.mercatus.org/emergent-ventures) is a grant program run by [Tyler Cowen](https://en.wikipedia.org/wiki/Tyler_Cowen) (an economist who writes Marginal Revolution) at the Mercatus Center. 

This repo has a CSV of all EV winners until December 2023. In addition, there is a Python file (search_winners.py) that uses Sentence Transformers to generate embeddings for each of their project descriptions. This enables easy semantic search for EV-funded projects, e.g. you can search for all funding relating to writing a book, or starting a podcast, or working on climate change, for example.

Usage for the Python script: just download the repo, install dependencies

```pip install``` 

and then: 

```python scripts/search_winners.py [query] [number-of-results]```

Note that the number-of-results argument is optional and defaults to 10. This returns 10 results. 

The scripts folder also contains generate_embeddings_py, which I use to generate embeddings for each EV winner's project description for semantic search. Usage is just:

```python scripts/generate_embeddings.py```

...which updates the data in /data, using the CSV file ev-winners.csv. 