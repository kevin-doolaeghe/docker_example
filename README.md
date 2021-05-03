# Créer un container Docker

Construire un nouveau container :

```
docker build -t [container] [chemin]
```

Télécharger un container provenant de Docker Hub :

```
docker pull [auteur]/[container]
```

Afficher la liste des containers locaux :

```
docker images
```

Démarrer un container :

```
docker run [container]
```

Intéragir avec un container :

```
docker run -it [container]
```

Afficher l'état des containers :

```
docker ps -a
```
