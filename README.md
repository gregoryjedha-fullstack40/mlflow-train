```
docker build . -t mlflow-train
docker tag mlflow-train gregoryjedha/mlflow-train
docker push gregoryjedha/mlflow-train
docker run gregoryjedha/mlflow-train
```
