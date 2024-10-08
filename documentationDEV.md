# Documentation développeur sur la structure du projet

## Structure pertinente

Les fondamentaux de la répartition de projet web, les dossiers`css` et `js` à la racine, restent pertinents dans le sens où on a pas spécialement envie de mélanger du code et une ressource importable comme une feuille de style.

Dans le répertoire `ejs`, le fichier `head.ejs` n'ont rien à faire là puisqu'ils sont intégralement vides, autant les supprimer pour éviter d'encombrer l'esprit des développeurs ou indiquer pourquoi ils sont vides.

On va aussi vouloir ramifier les répertoires `js`, `ejs` et `css` au maximum pour que le chemin d'un fichier puisse nous dire à quoi il sert et minimiser la taille des commentaires et garder le code un peu plus lisible.
