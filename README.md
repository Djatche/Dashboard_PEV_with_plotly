# Dashboard PEV avec plotly

![Dashboard](newplot(2).png "Dashboard PEV")

Mensuellement les FOSA sont appelées à analyser leur données pour prendre des décisions. Leur analyse consiste à catégoriser les aires de santé. Deux critères sont utilisé: l'accessibilité et l'utilisation du service.
- Le taux de couverture en DCTHepBHIb1 ou PENTA1 permet d’évaluer l’accessibilité au service
- Le Taux d’ abandon permet d’apprecier l’utilisation des services
On dénombre 4 catégories:

|   accessibilité    |   utilisation    |   catégories    |       
|:-:    |:-:    |:-:    |
|   >=90    |   <10    |   cat 1    |       
|   >=90    |   >=10    |   cat 2    |       
|   <90    |    <10   |   cat 3    |       
|   <90    |    >=10   |    cat 4   |    

Le dashboard realisé avec plotly python nous permet de visualiser les performances sous forme de diagramme de bulles.
Chaque FOSA/aire de santé est représenté par une bulle dont la couleur permet d'identifier la catégorie. La taille de la bulle est proportionnelle à la population cible.
Ce dashboard est d'utilisation facile.    
