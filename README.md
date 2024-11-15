# Chest-Disease-Classification-from-Chest-CT-Scan-Image


## Workflows

1. Update config.yaml
2. Update params.yaml
3. Update the entity
4. Update the configuration manager in src config
5. Update the components
6. Update the pipeline 
7. Update the main.py
8. Update the dvc.yaml 






## Git commands

```bash
git add .

git commit -m "Updated"

git push origin main
```

## How to run?

```bash
conda create -n chest python=3.8 -y
```

```bash
conda activate chest
```

```bash
pip install -r requirements.txt
```

```bash
python app.py
```



<!-- import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1) -->

```bash
MLFLOW_TRACKING_URI=htt
MLFLOW_TRACKING_USERNAME=man
MLFLOW_TRACKING_PASSWORD=8
python script.py
```

```bash
export MLFLOW_TRACKING_URI=
export MLFLOW_TRACKING_USERNAME=m
export MLFLOW_TRACKING_PASSWORD=81b8e1
```

```bash
os.environ['MLFLOW_TRACKING_URI'] = 
os.environ['MLFLOW_TRACKING_USERNAME'] = 
os.environ['MLFLOW_TRACKING_PASSWORD'] = 
```