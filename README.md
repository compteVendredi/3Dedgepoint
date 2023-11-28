# 3Dedgepoint

Projet sur la reconnaissance des points bords dans un nuage de points 3D.

Description des jupyter-notebooks :
- reseau-simple : Une architecture (simple) basée sur un MLP faite sous pytorch.
- performance-reseaux : Une explication sur la lenteur de reseau-simple et des améliorations qu'il y a eu, en particulier sur le dataloader.
- pcednet : L'architecture PCEDNet faite sous pytorch.

Les 3 suivants correspondant à ceux qui sont évoqués dans performance-reseaux :
- reseau-simple-avec-keras : La même architecture que réseau-simple mais faite sous keras/tensorflow.
- (à titre indicatif) chargement-parall-le : Le chargement des données en parallèle.
- (à titre indicatif) chargement-parall-le-dataset-contigu : Le chargement des données en parallèle avec la contiguïté des données.

Et
- a.png : Une image utilisée dans un jupyter-notebook.
