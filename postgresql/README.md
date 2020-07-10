
# PostgreSQL et PgAdmin

Espace de travail sur POSTGRESQL et PGADMIN.

## Pre-réquis

Avant de lancer le postgresql et le pgAdmin, il faut :

* créer de nouveau volume pour postgresql et pgadmin ;
* Remplacer les volumes :
  * demo1-data par le nouveau volume de postgresql ;
  * demo1-pgadmin-data par celui créé pour pgadmin ;
* Se placer dans le même dossier que le ***docker-compose.yml*** ;
* Lancer la commande : `docker-compose up`
