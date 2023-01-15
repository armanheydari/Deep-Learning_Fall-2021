if you want to test the model,first run the whole 'Define and train the model',
if you want to use the trained weights, you must have the model weights (our_model.h5)
beside the project.ipynb file. and the 'is_load_model' hyperparameter must set to True.
(it is true now)
second, run the whole Test section. and then you can use the predict method like this:
predict('path/to/image')