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



## Live matarials docs

[link](https://docs.google.com/document/d/1UFiHnyKRqgx8Lodsvdzu58LbVjdWHNf-uab2WmhE0A4/edit?usp=sharing)


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

import dagshub
dagshub.init(repo_owner='mandar6988', repo_name='mlflow_experiments', mlflow=True)

<!-- import mlflow
with mlflow.start_run():
  mlflow.log_param('parameter name', 'value')
  mlflow.log_metric('metric name', 1) -->

```bash
MLFLOW_TRACKING_URI=https://dagshub.com/mandar6988/mlflow_experiments.mlflow /
MLFLOW_TRACKING_USERNAME=mandar6988 /
MLFLOW_TRACKING_PASSWORD=81b8e17e1b4b4ae450196f6acd3d229ab74d7592 /
python script.py
```

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/mandar6988/mlflow_experiments.mlflow
export MLFLOW_TRACKING_USERNAME=mandar6988
export MLFLOW_TRACKING_PASSWORD=81b8e17e1b4b4ae450196f6acd3d229ab74d7592
```

```bash
os.environ['MLFLOW_TRACKING_URI'] = 'MLFLOW_TRACKING_URI'
os.environ['MLFLOW_TRACKING_USERNAME'] = 'mandar6988'
os.environ['MLFLOW_TRACKING_PASSWORD'] = '81b8e17e1b4b4ae450196f6acd3d229ab74d7592'
```