Experiment tracking is the process of recording all the important components such as hyper parameters, metrics, models and artifacts like plots PNG images, files etc. Experiment tracking helps to reproduce the old results by using the stored parameters. Under one experiment different runs can be created and by changing the parameters value we can evaluate model performance. And easily do the model performance comparison and finalize the optimal model for production. MLFlow is the widely used tool for experiment tracking across organizations.

1. Create conda Environment
2. Train a Basic Machine Learning classifier using Random Forest
3. Create experiment with basic classifier and records metrics
4. Fine tune the model using hyper parameter tuning random search CV method
5. Create another experiment and log all hyper parameters, metrics, and artifacts which contains model, roc_auc curve PNG, confusion Matrix PNG.



## Steps:

```bash
conda create -n mlops-juy python=3.9 ipykernel -y
conda activate mlops-juy
```

```bash
touch requirements.txt
pip install -r requirements.txt
```

* run juypyter-lab in same env and open `MLFLOW Live Demo`

* after runing the juypyter notebook run the below command in terminal
```bash
mlflow ui
```