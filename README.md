# Scanner de ports
```
 ____   ___  ____ _____   ____   ____    _    _   _ _   _ _____ ____
|  _ \ / _ \|  _ \_   _| / ___| / ___|  / \  | \ | | \ | | ____|  _ \
| |_) | | | | |_) || |   \___ \| |     / _ \ |  \| |  \| |  _| | |_) |
|  __/| |_| |  _ < | |    ___) | |___ / ___ \| |\  | |\  | |___|  _ <
|_|    \___/|_| \_\|_|   |____/ \____/_/   \_\_| \_|_| \_|_____|_| \_\
```
## Présentation
Script Python (réalisé par Pierre Chaussard) qui permet de scanner tous les ports TCP communs d'un hôte connu (IP/Host).

Cet outil ne peut être utilisé qu'à des fins légales. Les utilisateurs assument l'entière responsabilité de toute action effectuée à l'aide de cet outil. L'auteur décline toute responsabilité pour les dommages causés par cet outil. Si ces termes ne vous conviennent pas, n'utilisez pas cet outil.

## Installation
1. Clonez le `repository`.
2. Installez les modules python suivants :
    - `pip install pyfiglet`.
    - `pip install socket`.
    - `pip install json`.
    - `pip install sys`.

## Utilisation
1. Lancement : `py main.py [ip/host]` (*par exemple : `py main.py 127.0.0.1`*).
2. Dans le dossier `src/`, vous pourrez trouver le rapport du scan précédement effectué dans un fichier `.txt`.

##### Développé par Pierre Chaussard.
