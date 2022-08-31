- 'Predictions' contain the predicted outputs of 10 epochs for each model.

- 'Proposed Models' contain the source code for the different proposed models. The raw data uses ir_datasets module*.

- 'Training and Eval' contains the code for preprocessing and evaluation of the models. 
	- 'Preprocessing' is used for preprocessing and saving training and evaluation data. This uses ir_datasets module.
	- 'Evaluation Preprocessing' converts and saves eval dataset into 2 files - inp.pkl (query-document pair) and out.pkl (target labels). This notebook uses ir_datasets module.
	- 'Evaluation Predictions' is used to create files containing predicted output for each model.
	- 'Evaluation' is used to evaluate the predicted outputs against ground truth labels to see how the models fared against each other using some evaluation metrics.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Please note that since the models were trained on Google Colab, the files' paths are in relation to Colab and not the local file system.

### The trained models are not included in this package because they are big in size. Instead, their output (the predictions) are saved in the 'Predictions' folder. The ir_datasets need to be loaded to use it to train the models. 
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*ir_datasets module is not included in this package because it is a big folder. The ir_datasets folder must be downloaded and placed within the 'Dissertation' folder.
