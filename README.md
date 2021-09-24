# Jupyter Intellisense and auto-complete bug fix

## To be run in jupyter 
- if autocomplete not working try this .but have to run in every single notebook

```
%config Completer.use_jedi = False
```

-  or you can upgrade jedi, work for you

```Jupyter Notebook
!pip install --upgrade jedi==0.17.2
```


## To run in command-line
```Shell
pip install --upgrade jedi==0.17.2
```
**END**


# Terminology
**Hyperparameters** are settings on the model which are not changed during training but can affect how quickly or how reliably the model trains, such as the number of clusters the model should identify.

A **loss function** is used to codify the model’s distance from this goal

**Training dataset:** The data on which the model will be trained. Most of your data will be here.

**Test dataset:** The data withheld from the model during training, which is used to test how well your model will generalize to new data.

**Model parameters** are settings or configurations the training algorithm can update to change how the model behaves.
