# Cartographie de l'équipement des gares SNCF

Projet personnel de cartographie de données ouvertes, réalisé en R.
La carte interactive permet d'explorer si les gares SNCF les plus fréquentées
sont aussi les mieux équipées et si les gares mieux équipées possèdent également le Wi-Fi.
Elle croise plusieurs jeux de données publiés par la SNCF.

**Carte interactive : https://heleniade.github.io/WiFi_Gare/**

### Bases de données utilisées :
- https://ressources.data.sncf.com/explore/dataset/gares-equipees-du-wifi/information/
- https://ressources.data.sncf.com/explore/dataset/gares-de-voyageurs/information/?disjunctive.segment_drg
- https://ressources.data.sncf.com/explore/dataset/equipements-accessibilite-en-gare/information/
- https://ressources.data.sncf.com/explore/dataset/frequentation-gares/information/?disjunctive.nom_gare&disjunctive.code_postal

### Librairies R utilisées :
- sf (lecture fichier .gson)
- leaflet (cartographie)
- dplyr (manipulation des données)
- tidyr(manipulation des données)
-  htmlwidgets (création d'un site HTML GitHub Pages)
- readr (lecture des bases de données)
