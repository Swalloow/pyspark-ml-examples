# pyspark-ml-examples
Spark ML Tutorial and Examples for Beginners

## How to start
Use Docker Images : https://hub.docker.com/r/jupyter/pyspark-notebook/

```
docker run -it --rm -p 8888:8888 --name jupyter \
-v /YOUR_DOWNLOAD_PATH/pyspark-ml-examples:/home/jovyan jupyter/pyspark-notebook start-notebook.sh
```

## Index
- **spark-ml-starter**: EDA, Preprocessing, Modeling, Evaluation, Tuning
- **spark-ml-gbt-pipeline**: GBTClassifier, Pipeline
- **spark-ml-recommendation-explicit**: Movie recommendation with Explicit Collaborative Filtering
- **spark-ml-recommendation-implicit**: Music recommendation with Implicit Collaborative Filtering
- **spark-ml-clustering**: Anomaly Detection in Network Trac with K-means Clustering

## Dataset
- Kaggle Titanic Dataset: https://www.kaggle.com/c/titanic/data
- MovieLens Dataset: https://grouplens.org/datasets/movielens/100k/
- Last.fm Music Dataset: http://www.dtic.upf.edu/~ocelma/MusicRecommendationDataset/lastfm-1K.html
- KDD Cup 1999 Dataset: http://www.kdd.org/kdd-cup/view/kdd-cup-1999/Data
