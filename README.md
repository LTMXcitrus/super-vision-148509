installation:
- npm install

lancement en local
- npm run start

______________________________________________________________________________________

**déploiement sur app-engine

pré-requis:
- git
- gcloud sdk (voir plus bas)
- nodeJS

Dans le dashboard app engine, création d'un "project" avec un ID

dans le répertoire de l'application:
"gcloud init" #connexion au compte google, configuration (j'ai choisi la config par défaut)
"gcloud app deploy" # déploiement de l'application, choix du project app engine correspondant (celui qu'on a créé ci-dessus)

on peut enfin accéder à l'appli à l'adresse: https://[ID-de-l'application].appspot.com
______________________________________________________________________________________
installation du sdk (linux):
- télécharger le sdk ici: https://cloud.google.com/sdk/docs/
une fois décomprimé dans le répertoire "dir":1
- ./google-cloud-skd/install.sh
rédemarrer le terminal
- ./google-cloud-sdk/bin/gcloud init

