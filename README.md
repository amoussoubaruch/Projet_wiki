# Projet_wiki

> Ce projet a pour but de récupérer les données des pages vues de wiki et d'en faire un dashboard 

> Etape 1 : Injection de données : 2 possibilités 

1. crawler directement le site pour récupérer la données et l'intégrer dans HDFS
2. Passer par S3 AWS

> La première solution a été testée

> Le script python à utiliser pour scapper le site https://dumps.wikimedia.org/other/pagecounts-raw/

> Intégrer ce programme dans un script shell pour l'injection de données

> Avant exécution donner les droits d'exécution sur le fihier.sh

```sh
$ chmod u+x envoie_hdfs.sh 
$ ./envoie_hdfs.sh
```

