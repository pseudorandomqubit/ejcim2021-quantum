# TP de programmation quantique

## Si vous n'utilisez pas mybinder

Tout ce qui suit est conditioné par votre OS et votre version de python:
- Windows (Python 3.6, Python 3.7, Python 3.8 64-bit version)
- MacOS (Python 3.6, Python 3.7, Python 3.8 64-bit version)
- Linux (Python 3.6, Python 3.8 64-bit version)

Si votre système ne rentre pas dans ces cases, vous aurez une erreur lors de l'installation via pip (pas forcément des plus explicite).
Notez que les distribs non standards de python (style Anaconda) ne sont pas supportées.

Idéalement, on fera le TP dans des notebooks jupyter. Il faut donc préalablement installer jupyter:

    pip install jupyter

On va utiliser la librairie python suivante pour le TP:

    pip install myqlm
    
Si vous voulez pouvoir afficher les circuits quantiques dans un notebook jupyter, il vous faudra installer les magics:

    python -m qat.magics.install

La doc de la librairie se trouve ici https://myqlm.github.io/

## Si vous utilisez mybinder

Normalement vous ne devriez jamais voir ce README 😲
