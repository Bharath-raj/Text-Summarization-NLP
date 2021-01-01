Open Terminal and CD to Project

conda create --name NLP_Python

activate NLP_Python

conda install -c anaconda nltk

python -m nltk.downloader stopwords

python -m nltk.downloader brown

python -m nltk.downloader punkt

python -m nltk.downloader averaged_perceptron_tagger

python -m nltk.downloader wordnet

Open Another Terminal and CD to Project

activate NLP_Python

jupyter notebook
