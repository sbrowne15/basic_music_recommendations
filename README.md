# basic_music_recommendations
Utilized the 1 Million Song dataset to create a music recommendation program based on overall popularity(naive/unpersonalized) and user selections(personalized/collaborative filter).  Recommendations can also be made by song title using the same logic as the user selections.  Correlations were made using Pearson Correlation Model.

Recommendations and the ability to make them are a cornerstone of most, if not all, media services regardless of medium (books, music, movies, etc.).  I was interested in "peeking behind the curtain" to get an idea of how this worked.  The next step would be to apply the program to the full dataset, develop a front-end for users to request recommendations based on songs, playlists, or artists, and finding more data to incorporate into this dataset to strengthen recommendations.

## Techniques Used and Dependencies
- Collaborative Filtering
- Python
- Jupyter
- pandas
- numpy
- scikit-learn
- [Recommenders.py](https://github.com/llSourcell/recommender_live/blob/master/Recommenders.py)

[pip](https://pip.pypa.io/en/stable/) will install missing dependencies.

Recommenders.py will need to be downloaded and saved to ...\anaconda3\Lib\site-packages

## Datasets
Publicly available from [Million Song Dataset](http://millionsongdataset.com/).  In an effort to speed up the processing, the dataset was parsed down to 10,000 songs.

## Acknowledgements
- [dvysardana](https://github.com/dvysardana) for creating Recommender.py
- [Siraj Raval](https://github.com/llSourcell) for being the link I followed to find Recommenders.py

## How to run
Start jupyter using jupyter notebook.
Run all cells in Music Recommender.ipynb.
