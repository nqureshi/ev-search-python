# This repo has moved

The Emergent Ventures winners data and the embeddings pipeline now live in the
site's repo: **https://github.com/nqureshi/ev-winners**

- Raw data (CSV): https://github.com/nqureshi/ev-winners/blob/main/pipeline/data/ev-winners.csv
- Scripts and instructions: https://github.com/nqureshi/ev-winners/tree/main/pipeline
- The site itself: https://evwinners.org

This repo is kept for its history only and is no longer updated. The last cohort
here is 58 (August 2026); newer cohorts are in ev-winners.

---

## What this was

Emergent Ventures (https://www.mercatus.org/emergent-ventures) is a grant program run by
[Tyler Cowen](https://en.wikipedia.org/wiki/Tyler_Cowen) at the Mercatus Center. This repo
held a CSV of all EV winners plus a Python script that used Sentence Transformers
(all-MiniLM-L6-v2) to embed each project description for semantic search.
