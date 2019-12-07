- L'implémentation initiale présentée dans la vidéo est faite en PHP (Laravel),
- Dans le souci de garder une adéquation entre la formation et le projet keepknowin, 
	il faut proposer une implémentation en Java.
- Cependant, proposer une architecture simple qui utilise Elasticsearch comme base de données, 
	puis rechercher et indexer les documents n'a pas d'enjeu pour le projet keepknowin.
- Il faut bien coupler Elasticsearch à MongoDB, utiliser MongoDB comme base de données primaire et Elasticsearch juste comme moteur 
d'indexation et de recherche qui est alimenté par les données de MongoDB. C'est à ce niveau que nous avons le problème qu'on essaye de résoudre.
