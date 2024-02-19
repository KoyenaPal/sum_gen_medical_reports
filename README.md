# Code for Comparative Study on Automatic Generation of Discharge Summary Reports

## Data
To create the training and testing datasets:
- Run the `Data_Analysis.ipynb` present in the `notebooks` folder. It would create all the setups given the MIMIC-III data.
- Then run, `Training_Testing_Data_Creation.ipynb` present in the same folder to split all the previously created setups into their relevant training and testing data files.

## Model Training
Each model, BART, T5, FLAN-T5, and Longformer, has their respective training notebooks in the `notebooks` folder. They are `BART Training.ipynb`, `T5 all.ipynb`, `New_T5_Fine_tuning.ipynb`, and `LED_all.ipynb` respectively.
