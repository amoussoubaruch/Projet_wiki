# Projet_wiki

> Ce projet a pour but de récupérer la donnée des pages vues de wiki et d'en faire un dashbord 

> Etape 1 : Ingestion de données : 2 possibilités 

1. crawler directement le site pour récupérer la données et l'intégrer dans HDFS
2. Passer par S3 AWS

> La première solution a été testé

> Le script python a utiliser pour scapper le site https://dumps.wikimedia.org/other/pagecounts-raw/

> Integer ce programme dans un script shell pour l'injestion de donner

> Avant exécution donner les droits d'exécution sur le fihier.sh

```sh
$ chmod u+x envoie_hdfs.sh 
$ ./envoie_hdfs.sh
```

