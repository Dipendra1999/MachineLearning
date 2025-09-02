# MachineLearning
This repo contain algorithms uses in machine learning
 * Online ML:- River module and Vowpal Wabbit
 river:-It is the result of a merger between cream and scikit-multiflow...

# how to open data sets into the local jupyter notebook by url
{% 
import pandas as pd
url='' # type the url in this inverted commas
data = pd.read_csv(url,sep=",") # use sep="," for coma separation. use sep="\t" for tab seperation.
data.describe()
%}
