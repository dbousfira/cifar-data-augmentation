Data augmentation - Cifar
==============================

La société "Little Sister" souhaite développer un nouveau type de caméras de surveillance pour l'espace publique.

Elle souhaite mettre en avant une fonctionnalité de reconnaissance d'éléments sur une image afin de pouvoir identifier des cas, des situations qui peuvent survenir dans la vie de tous les jours.

Elle possède un modèle que vous lui avez fourni précédemment, qui permet de détecter des éléments qu'on peut retrouver sur une image. Première étape vers leur objectif final : prévenir des situations pouvant être dangereuses, voir des incivilités.

La performance de ce modèle ne répond aujourd'hui pas aux espérances de la société. Il faut donc tout d'abord **analyser la performance d'un modèle sans préprocessing **et essayer d'améliorer la qualité du modèle avec du préprocessing (ici data augmentation).

Project Organization
------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   └── raw            <- The original, immutable data dump.
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries.
    │
    ├── notebooks          <- Jupyter notebooks.
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py



--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
