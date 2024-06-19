# Chicken-Disease-Classification

### Project Workflows
1. update config.yaml
2. Update secrets.yaml[Optional]
3. update params.yaml
4. update the entity
5. update the configuration manager in src config
6. update the components
7. update the pipeline
8. update the main.py
9. update the dvc.yaml
10. update the app.py


### How to run the projet

### STEPS:

Clone the repository

```bash
https://github.com/MannShrestha/Chicken-Disease-Classification.git
```

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n venv python==3.8 -y

OR

conda create -p venv python==3.8 -y
```

```bash
conda activate venv
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### After Training the model - to visualize Training report through Tensorboard
```bash
tensorboard --logdir artifacts/prepare_callbacks/tensorboard_log_dir/
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up you local host and port
```


### DVC cmd

1. dvc init
2. dvc repro
3. dvc dag
