# project-web-de-datos-2022

## CSV to RDF

En windows, desde la terminal entrar a la carpeta tarql-1.2/bin

 ```cd tarql-1.2/bin``` 

Luego ejecutar el siguiente comando para obtener el rdf que se guardará en la carpeta `lol-data-rdf`

### Champions

 ```tarql ../../lol-data-sparql/champions.sparql ../../lol-data-csv/champions.csv > ../../lol-data-rdf/champions.ttl```

 ### Matches

  ```tarql ../../lol-data-sparql/matches.sparql ../../lol-data-csv/matches.csv > ../../lol-data-rdf/matches.ttl```


 ### Teams
  ```tarql ../../lol-data-sparql/teams.sparql ../../lol-data-csv/teams.csv > ../../lol-data-rdf/teams.ttl ```


 ### Players
 ```tarql ../../lol-data-sparql/players.sparql ../../lol-data-csv/players.csv > ../../lol-data-rdf/players.ttl```


 ### Players statistics per match
 ```tarql ../../lol-data-sparql/players_stats_per_match.sparql ../../lol-data-csv/players_stats_per_match.csv > ../../lol-data-rdf/players_stats_per_match.ttl```


 ### Casters
 
  ```tarql ../../lol-data-sparql/casters.sparql ../../lol-data-csv/casters.csv > ../../lol-data-rdf/casters.ttl```


## SPARQL queries

* Quién es el más cool?