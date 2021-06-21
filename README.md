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
