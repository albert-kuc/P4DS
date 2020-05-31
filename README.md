Programming for Data Science (p4ds)
--------------
[![N|Solid](https://www.conted.ox.ac.uk/www/static/images/oudce_logo_2.png)](https://www.conted.ox.ac.uk/courses/programming-for-data-science?code=O19P732COW)

Course provided by Department for Continuing Education at University of Oxford. \
[Course website](https://www.conted.ox.ac.uk/courses/programming-for-data-science?code=O19P732COW)

#### Course Programme (provisional)
Week 1:  Introduction to the course. Basic overview of Machine Learning. Linear Regression example.\
Week 2:  Machine Learning: a data-science preprocessing pipeline.\
Week 3:  Supervised Learning with scikit-learn: regression.\
Week 4:  Supervised Learning with scikit-learn: classification.\
Week 5:  Multi-class classification. Classification with Decision Trees. Introduction to Neural Networks with  scikit-learn.\
Week 6:  Deep Learning: Feed-forward Neural Networks with Tensorflow and Keras.\
Week 7:  Deep Learning: training deep models.\
Week 8:  Convolutional Neural Networks for Image Processing. Recurrent Neural Networks for Time Series Prediction.\
Week 9:  Dimensionality reduction and Unsupervised Learning with scikit-learn.\
Week 10: Natural Language Processing: an overview and some RNN applications (nlkt; spaCy; Keras). Final assignment.

#### Solvied Anaconda Tensorflow installation issue:
The issue:\
* No module found error in Jupyter Notebook even with Tensorflow 2.1 present at the environment installed package list.\
* Lower version tensorflow installed instead of tensorflow 2.

Solution found with [Stackoverflow.org](https://stackoverflow.com/questions/38221181/no-module-named-tensorflow-in-jupyter)
Updated solution found with [365datascience.com](https://365datascience.com/install-tensorflow-2-anaconda/)

From Anaconda Navigator select the virtual environment and open terminal. Run the following line to install tensorflow 2:
```
conda install tensorflow 
```
Next re-install jupyter notebook to make sure that notebook recognizes tensorflow. 
```
conda install jupyter notebook
```
Previously used the following line but as for 2020/05/31 it ended with installing tensorflow 1.13 instead.
"conda install -c conda-forge tensorflow"