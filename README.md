## lamanu_sql
# Qu'est-ce qu'on sait ?
[27/02/23] 
* On sait créer une base de données ```CREATE DATABASE <nom de la bdd>```
* Ajouter des éléments de la base données ``` INSERT INTO <nom de la table> [(nom de colonnes)] [VALUES] (val, val2, val3)``` 
* Afficher des éléments de la bdd ```SELECT * FROM <nom de la table>```
* Modifier une table ```ALTER TABLE <nom de la table> [l'altération] ```
* On sait rechercher des élements par critères ``` SELECT * FROM <nom de la table> WHERE critère ```
* Supprimer des bdd ```DROP DATABASE <nom de la bdd>```

* On peut créer des tables ```CREATE TABLE {} ```
* On peut supprimer des tables  ``` DROP TABLE  ```
* On sait faire une jointure ```SELECT * from <nom de table> INNER JOIN <nom de table bis> ON table1.id = table2.id```
* On sait modifier des enregistrements ```UPDATE <nom de table> SET <nom le colonne> = <val>, <nom de la colone 2> = val2, .... WHERE col = val; ```
*  On sait faire des fonctions aggrégations (avg, count, sum)
* On sait supprimer des enregistrements ```
DELETE FROM table_name WHERE condition;```
* Utilisation de la limit pour définir le nombre de ligne à renvoyer 
* On sait afficher en triant ```ORDER BY <colonne(s)>[desc|asc] ```
* On sait regrouper nos informations ```GROUP BY ```
* On sait faire une sous requête 
* MIN , MAX , renvoie le min ou le max d'une plage de données
* ALIASES permet de renomer une table
