# Configurer son nom 
````
git config --global user.name
````

# Configurer son mail 
````
git config --global user.email
````

# Créer un nouveau repo
```
git init
```

# Ajouter un fichier au suivi Git
````
touch README.md
git add ./README.md
````

# Voir l'état de mon répertoire de travail
````
git status
````

# Connecter le répertoire local avec le répertoire en ligne
````
git remote add origin 'url-du-remote'
````

# Envoyer le projet 
````
git push -u origin master
````

# Récuperer le répo
````
git clone 'url-du-remote' 'nom du dossier'
````
# Ignorer un fichier
````
touch fichier-cache.txt
touch toto.js
touch yolo.js
touch .gitignore
````

Ajouter fichier-cache.txt dans le fichier .gitignore :

** Ignorer un fichier **
./fichier-cache.txt

** Ignorer un type de fichier **
*.txt

** Ignorer un fichier avec une règle **
t*.js