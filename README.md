# DataChallenge
Data Challenge pour Anna et Malek

Pour la regression
Pour importer les donnees, faire:
import pandas as pd
train=pd.read_parquet("/chemin/train.parquet")
test=pd.read_parquet("/chemin/test.parquet")

Ensuite pour telecharger les donnees, faire
linreg_prediction.to_parquet("/chemin/linreg_prediction.parquet", engine='pyarrow', index=True)
rf_prediction.to_parquet("/chemin/rf_prediction.parquet", engine='pyarrow', index=True)
gb_prediction.to_parquet("/chemin/gb_prediction.parquet", engine='pyarrow', index=True)
