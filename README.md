
# 🏗️ Presentation du projet

Ce projet a été réalisé dans le cadre de la prise en main des outils tels que: `FastAPI`, `Uvicorn`, `Venv`; A l'aide du langage `Python`.

## Structure du projet
  Le projet comprend: 

  1. Serveur **uvicorn**
  2. Une source de données JSON (fichier `pockenmons.json`)
  3. Un fichier d'entrée `main.py` pour l'excution du projet

# 🚀 Exécution

  Pour démarrer le projet, il suffit de: 

  1. Cloner le projet à partir du lien: ``
  2. A partir du répertoire racine executer la commande:  ``
  3. Naviguez sur cette adresse `http://localhost:8000/docs#/default/read_root__get` pour visiter l'API.

### Architecture de l'API

  L'API comprend 7 endpoints

  1. http://localhost:8000/total_pokemons permet d'obtenir le nombre total des Pokemons
  2. http://localhost:8000/total_pokemons permet d'obtenir la liste des Pokemons
  3. http://localhost:8000/pokemons/1 permet de récupère un pokemon specific par son ID
  4. http://localhost:8000/pokemons/3 permet de supprimer l' pokemon d'ID 3
  5. http://localhost:8000/types permet de récupérer la liste des types de pokemon
  6. http://localhost:8000/pokemons/search/?types=Dratini%20Dragon&evo=false&sortby=id&order=desc permet de filtrer la liste des pokemons sur différentes propriétés (`id`, `name`, `évolution` ...)
  
  ![alt text](assets/image.png)




