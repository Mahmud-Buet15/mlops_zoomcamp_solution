## Understanding MLFlow 

### MLFlow commands
- Check available options: `mlflow`
- Check version: `mlflow --version`
- Get details of an option: `mlflow server --help`
- Configure experiment tracker 
    - on local machine's **./mlruns** directory: `mlflow server`
    - on sqlite server `mlflow server --backend-store-uri sqlite://mlflow.db`



### Notes
- **01_duration_prediction.ipynb**  
  - Getting started with mlflow. 
  - Backend: local filesystem URIs
- **02_duration_prediction_hyperparameter_tuning.ipynb**  
  - Tracking experiments of hyperparameter tuning. 
  - Backend: local filesystem URIs
- **03_experiment_on_sqlite.ipynb**  
  - Tracking experiments of hyperparameter tuning. 
  - Backend: sqlite db
- **04_interacting_using_api.ipynb**
  - Interacting with mlflow using API
  - Backend: sqlite db


### Other docs
- Hyperopt documentation on search space: https://hyperopt.github.io/hyperopt/getting-started/search_spaces/
