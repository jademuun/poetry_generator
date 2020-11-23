# Generátor poezie

Našim cieľom bolo spraviť aplikáciu, ktorá po zadaní slova (v anličtine) vygeneruje báseň ako predikciu natrénovaného modelu. Ide teda o interaktívny widget s Pythonovským backendom. Na vytvorenie widgetu sme využili Pythonovskú knižnicu [ipywidgets](https://ipywidgets.readthedocs.io/en/latest/). Následne sme využitím [voila](https://voila.readthedocs.io/en/stable/using.html) lokálne vytvorili takúto aplikáciu.

Ako trenovacie data sme si zobrali [597 básní](https://www.kaggle.com/jenlooper/597-poems-by-emily-dickinson) od Americej spisovateľky [Emily Dickinson](https://en.wikipedia.org/wiki/Emily_Dickinson). Momentálne pracujeme na čistení ďalších dvoch datasetov básní od C. Bukowski, W. Shakespear, na ktoré chceme taktiež tento model vyskúšať.

[Model](https://github.com/katarinagresova/M7DataSP_2020/blob/master/assignment_07/PoetryCharByChar.ipynb) sme vytvorili pomocou dvoch LSTM vrstiev a funguje na báze učenia sa charakterov. Podarilo sa nám urobiť aj model, ktorý sa učí zo slov a v budúcnosti sa pokúsime tieto modely porovnať.

Nakoniec sme túto aplikáciu pushli na server [heroku](www.heroku.com).

# Voilá
# https://generator-poezie.herokuapp.com/

