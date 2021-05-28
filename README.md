# TP de programmation quantique


La doc de la librairie se trouve ici https://myqlm.github.io/


## Si vous préférez ne pas polluer votre système et travailler directement dans une VM:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pseudorandomqubit/ejcim2021-quantum/main?filepath=notebooks%2Foverview.ipynb)

## Si vous préférez travail en local sur votre machine ( moins de latence et probablement meilleures performances )

Tout ce qui suit est conditioné par votre OS et votre version de python:
- Windows (Python 3.6, Python 3.7, Python 3.8 64-bit version)
- MacOS (Python 3.6, Python 3.7, Python 3.8 64-bit version)
- Linux (Python 3.6, Python 3.8 64-bit version)

Si votre système ne rentre pas dans ces cases, vous aurez une erreur lors de l'installation via pip (pas forcément des plus explicite).
Notez que les distribs non standards de python (style Anaconda) ne sont pas supportées (la lib étant cross-compilé pour la distrib standard seulement).

Le plus simple pour installer la lib est de faire ça dans un virtualenv:

    virtualenv myqlm
    source myqlm/bin/activate
    

Idéalement, on fera le TP dans des notebooks jupyter. Il faut donc préalablement installer jupyter:

    pip install jupyter

On va utiliser la librairie python suivante pour le TP:

    pip install myqlm
    
Si vous voulez pouvoir afficher les circuits quantiques dans un notebook jupyter, il vous faudra installer les magics:

    python -m qat.magics.install

