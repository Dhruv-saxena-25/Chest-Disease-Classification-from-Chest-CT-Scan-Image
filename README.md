# Chest-Disease-Classification-from-Chest-CT-Scan-Image

- [Data link](https://drive.google.com/file/d/1z0mreUtRmR-P-magILsDR3T7M6IkGXtY/view?usp=sharing)

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

### Mlflow dagshub connection uri
    
``` bash

MLFLOW_TRACKING_URI=https://dagshub.com/Dhruv-saxena-25/Chest-Disease-Classification-from-Chest-CT-Scan-Image.mlflow \
MLFLOW_TRACKING_USERNAME=Dhruv-saxena-25 \
MLFLOW_TRACKING_PASSWORD=c89afa3d5cb46cd21a0333290065b3e3d17ac349 \
python script.py

```


### RUN from bash terminal

```bash
export MLFLOW_TRACKING_URI=https://dagshub.com/Dhruv-saxena-25/Chest-Disease-Classification-from-Chest-CT-Scan-Image.mlflow

export MLFLOW_TRACKING_USERNAME=Dhruv-saxena-25

export MLFLOW_TRACKING_PASSWORD=c89afa3d5cb46cd21a0333290065b3e3d17ac349

```



### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag