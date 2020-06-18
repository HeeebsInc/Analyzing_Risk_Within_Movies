# Analyzing Risk Within Movie Genres


## Packages 

```python 
import matplotlib.pyplot as plt
import pandas as pd 
import seaborn as sns
```

If a company is trying to enter the movie industry or create their first film, they must consider budget.  Considering movies do not have unlimited budget, you can approach this problem using a risk analaysis for each Genre.  


### Goals

- Use existing data from [MovieLens] (https://grouplens.org/datasets/movielens/) and [TMBD](https://www.kaggle.com/juzershakir/tmdb-movies-dataset) to determine if there is a difference in risk between genres
  - Is one genre less risky than another? 
- **Risk** is defined as the standard deviation divided by the mean
- Understand the distribution within each genre and whether there is noise

