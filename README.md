# Emergent Ventures Embeddings-Based Search

Emergent Ventures (https://www.mercatus.org/emergent-ventures) is a grant program run by Tyler Cowe (an economist who writes Marginal Revolution) at the Mercatus Center. 

This repo has a CSV of all EV winners until December 2023. In addition, there is a Python file (search_winners.py) that uses Sentence Transformers to generate embeddings for each of their project descriptions. This enables easy semantic search for EV-funded projects, e.g. you can search for all funding relating to writing a book, or starting a podcast, or working on climate change, for example.

Usage for the Python script: just download the repo, install dependencies

```pip3 install``` 

and then: 

```python3 search_winners.py [query] [number-of-results]"```

Note that the number-of-results argument is optional and defaults to 10. This returns 10 results. 