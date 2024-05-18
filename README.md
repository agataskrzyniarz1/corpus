## Objectif du projet
L'objectif de ce projet est de créer un corpus pour la traduction automatique. En faisant le web scraping, j'ai collecté les articles à partir du site de l'Université de Varsovie (https://www.uw.edu.pl/) en polonais ainsi que leurs traductions en anglais à partir de la version anglaise du même site (https://en.uw.edu.pl/).

Le corpus de référence utilisé dans le projet est [Helsinki-NLP/europarl](https://huggingface.co/datasets/Helsinki-NLP/europarl), qui contient des corpus parallèles récupérés à partir du site web du Parlement européen. J'ai utilisé un corpus avec une combinaison linguistique anglais-polonais. Le corpus contient une colonne 'translation' où se trouvent des phrases en anglais ainsi que leurs équivalents en polonais.

## Traduction automatique
La traduction automatique est le processus de traduction automatique de texte d'une langue à une autre à l'aide d'un ordinateur, sans intervention humaine. Les corpus sont essentiels pour l'entraînement et l'évaluation de la qualité des modèles de traduction automatique. Ce sont des ensembles de textes dans deux langues ou plus, utilisés pour l'apprentissage par les modèles. Plus le corpus est grand et diversifié, mieux le modèle peut apprendre à traduire des textes.
