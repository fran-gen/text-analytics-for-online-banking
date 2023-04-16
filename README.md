# Text Analytics for online banking
**Francesco Paolo Gentile** 
fra.fran.francesco@gmail.com

## _Description_

In this project, I provide text analytics for a dataset containing public available online banking reviews. Specifically, I provide an LDA topic model of such reviews as well as a sentiment analysis using BERT.

## _Tech used_
- Anaconda
- Jupyter Notebook
- Python 3.8

After having installed Anaconda on your system ([installation link](https://www.anaconda.com/products/individual#Downloads)), you can install Jupyter Notebook from within Anaconda itself. Alternatively, you can install Jupyter Notebook via pip ([link](https://jupyter.readthedocs.io/en/latest/install/notebook-classic.html)).

The **jupyter contrib nbextensions** Python package contains a code-folding extension that can be enabled within the notebook that allows to collapse the headings and the cells below them, so as to better visualize the notebook. You can install [jupyter contrib nbextensions](https://github.com/ipython-contrib/jupyter_contrib_nbextensions) via the following two commands:

```sh
pip install jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
```

I would also recommend to download the **jupyter nbextensions configurator** package. This provides an extra tab in your Notebook interface from where you can easily (de)activate all installed extensions.

Installation:

```sh
pip install jupyter_nbextensions_configurator
jupyter nbextensions_configurator enable --user
```
You can then follow this [tutorial](https://www.youtube.com/watch?v=_UG7lD_xfo8) on how to set up this functionality on Jupyter Notebook. 

## _Python libraries_
The following libraries need to be installed: 
- gensim
- numpy 
- matplotlib
- nltk
- pandas
- pickle
- operator
- pyLDAvis
- seaborn
- scikit-learn
- spacy (I used version 3.0.1)
- tensorflow (version 2.6.0)
- tensorflow_hub 
- tensorflow_text
- textacy
- wordcloud 

These libraries can be installed via pip:

```sh
pip install <NAME PACKAGE>
```



 
