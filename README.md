# CoWord
Preliminary notebook of CoWord co-occurece tool from HTRC Torchlite Hackathon

This notebook was created as part of the [HTRC TORCHLITE Hackathon](https://htrc.github.io/torchlite-hackathon/cfp.html). I was interested in exploring the co-occurrence of words within sets of texts and utilized the [Toni Morrison 10](https://analytics.dev.htrc.indiana.edu/publicworksets/43febde8-025f-49c9-aeec-7358ea788f3f) workset for testing this file. 

For a given workset, you can supply a keyword. The notebook will lemmatize that keyword and generate a list of all of the (lemmatized) tokens that appear on the same page as that word within the volumnes contained in the workset. It will generate:
1. A bar chart of the number of times the keyword appears in each of the volumes in the workset
2. A wordcloud of the nouns that appear on the same page as that key word most frequently across the workset
3. A table of the most words that co-occur most frequently alongside the keyword within each volume. 
