# Topic Modeling
In the [`topic_modeling.ipynb`](topic_modeling.ipynb) notebook, we are doing topic modeling based on available Python packages in this research field.

## Required Software
* [Java (JDK >= 16)](https://www.oracle.com/java/technologies/downloads/): Java SE Development Kit
* [Apache Ant (version >= 1.10.10)](https://ant.apache.org/bindownload.cgi): supplies a number of built-in tasks allowing to compile, assemble, test and run Java applications.
* [MALLET 2.0.8](https://mallet.cs.umass.edu/download.php): MAchine Learning for LanguagE Toolkit

## Required Python packages
For this notebook, required Python packages are:
* `nltk`: the [Natural Language Toolkit](https://www.nltk.org/)
* `gensim/3.8.3`: the ["*fastest library for training of vector embeddings*"](https://radimrehurek.com/gensim_3.8.3/)
* `spacy`: [Industrial-Strength Natural Language Processing](https://spacy.io/)
* `pyLDAvis/3.3.1`: [Python library for interactive topic model visualization](https://pypi.org/project/pyLDAvis/)

To install them and other dependencies, use `pip` in a Unix-like shell:
```Bash
# Prepend both commands with a "!" if you run them in a notebook cell
pip install matplotlib numpy pandas click==7.1.2
pip install nltk gensim==3.8.3 spacy pyLDAvis==3.3.1
```

## Required spaCy English vocabulary
To install the English vocabulary:
```Bash
# Prepend the command with a "!" if you run it in a notebook cell
python -m spacy download fr_core_news_sm
```
