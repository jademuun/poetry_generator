# [Poetry Generator](https://generator-poezie.herokuapp.com/)

Goal of this application is to present our work and capabilities of neural networks to learn language concepts and generate new poems based on given word. 

Created [neural network](https://github.com/katarinagresova/M7DataSP_2020/blob/master/assignment_07/PoetryCharByChar.ipynb) is composed of two LSTM layers and is learning text by characters. Learning dataset is composed of [597 poems](https://github.com/katarinagresova/M7DataSP_2020/blob/master/assignment_07/data/emily-together.txt) from American poet [Emily Dickinson](https://en.wikipedia.org/wiki/Emily_Dickinson) (With small changes was this datased taken from [kaggle 597 poems by Emily Dickinson](https://www.kaggle.com/jenlooper/597-poems-by-emily-dickinson)).

Application was created using python. Interactive widgets were created with help of python library [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/) and work of turning it into standalone web application was done by [Voilà](https://voila.readthedocs.io/en/stable/using.html). To host this application we use [Heroku](www.heroku.com) server.

### More work in progress

* we are cleaning poetry datasets from Charles Bukowski and William Shakespeare -- we would like to train our model on this datasets as well
* we created model that is learning text by words -- we would like to compare this model with model learning by characters
