Programming for Data Science (p4ds)
--------------
[![N|Solid](https://www.conted.ox.ac.uk/www/static/images/oudce_logo_2.png)](https://www.conted.ox.ac.uk/courses/programming-for-data-science?code=O19P732COW)

Course provided by Department for Continuing Education at University of Oxford. 
[Course details](https://www.conted.ox.ac.uk/courses/programming-for-data-science?code=O19P732COW)

#### Anaconda Tensorflow issue:
"Tensorflow - No module found" in Jupyter Notebook even with Tensorflow 2.1 present on environment installed package list.
Solution found with [Stackoverflow.org](https://stackoverflow.com/questions/38221181/no-module-named-tensorflow-in-jupyter)

In conda terminal run one after another:
```
conda install -c conda-forge tensorflow 
```

```
conda install jupyter notebook
```