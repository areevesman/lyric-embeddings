## Lyric-based song recommendation with Doc2Vec embeddings and Spotify's API

The notebook `train_example.ipynb` does the following:
- loads data from the [musiXmatch dataset](http://millionsongdataset.com/musixmatch/)
- trains song embeddings based on lyrics using [gensim](https://radimrehurek.com/gensim/models/doc2vec.html) and Doc2Vec
- applies t-SNE for dimensionality reduction and visualizes the results with plotly

Please see the Medium post for more details.
