# Démonstration YOLOv12

Ce dépôt illustre comment utiliser un modèle YOLOv12 à travers une petite interface Streamlit. L'application permet de téléverser une image, de lancer la détection d'objets puis d'afficher l'image annotée.

## Structure du dépôt

- `yolotest/appGem/appGem.py` : l'interface Streamlit qui appelle la fonction `run_detection` pour exécuter la détection.
- `yolotest/appGem/appGem.pyproj` et `yolotest/appGem.sln` : fichiers de configuration Visual Studio pour ce projet.
- `yolotest/appG` : projet d'exemple fourni vide.
- `yolotest/exemple.txt` : simple fichier texte utilisé comme exemple.

Le code suppose l'existence d'un fichier `detect.py` contenant la fonction `run_detection` ainsi qu'un modèle entraîné `best.pt` dans `yolov12/models`.

## Objectif

L'objectif est de montrer comment intégrer facilement la détection YOLOv12 dans une application web interactive. Après avoir sélectionné une image, l'utilisateur peut lancer la détection et visualiser immédiatement le résultat.
