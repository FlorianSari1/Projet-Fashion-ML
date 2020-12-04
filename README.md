Ce projet consiste à implémenter une ia en python avec le framework Keras et le dataset Fashion_MNIST, et d'avoir un score > 95%.
La difficulté principale était d'appréhender l'implémentation de sous couches du model afin d'optimiser le temps pour ne pas faire des entraînements de 200 epochs pour rien.
Le model réussit à atteindre ~95.22%, masi réussit parfois à atteindre des scores comme 96% en trichant (apprenant par coeur le dataset) 
Cet exercice occupant tous les TP m'a appris à définir l'architecture générale que l'on peut avoir en machine Learning à savoir le chargement des données, le préprocessing de ces dernières, l'implémentation du model avec les données, l'entraînement de celui-ci; Et pour finir l'inférence à partir du model généré dans un fichier .h5
