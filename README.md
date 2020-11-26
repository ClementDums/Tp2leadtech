# Tp2leadtech

# Conventions code

Il y'a des fichiers sans aucun commentaires alors qu'ils sont difficiles à comprendre. Il faudrait rajouter un minimum sur certains fichiers.

Avoir une norme unique de nommage de variable pour certains fichiers, certaines fois les variables sont à la fois en snake case et en camel case.

Avoir une norme unique d'indentation. Certaines fois je récuppère des fichiers mal indentés.

Vérifier le nommage des variables, parfois je me retrouve avec des noms de variables avec des fautes de frappes ou d'anglais.

Optimiser le nombre de variables, ça arrive qu'on recrée des variables sans forcement que ce soit utile.


# Infrastructure

### Ressources
- 2 développeurs payés 30 000€ par an pour se charger des bugs et des évolutions de l'API = 90 000€/an.
- 1 développeur ElasticSearch payé 36 000€ par an pour se charger du moteur de recherche.
- 1 devOps payés 36 000€ par an pour se charger principalement de l'infrastructure et de la gestion du cache.
- ### Ressource : 162 000€/an

### Stockage 

- Stockage des fichiers images : 10 000 * 300
- Stockage des liens d'images sur du NoSQL

- Gesiton du cache avec une solution AWS et Redis

### Recherche
- Elastic Search comme moteur de recherche
