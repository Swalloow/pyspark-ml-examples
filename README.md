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
- **spark-ml-explicit-recommendation**: Movie recommendation using Collaborative Filtering

## Dataset
- Kaggle Titanic Dataset: https://www.kaggle.com/c/titanic/data
- MovieLens Dataset: https://grouplens.org/datasets/movielens/100k/
