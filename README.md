# Reconnaissance des digits audio

## Organisation du dossier git

```
.
│   Digits_Recognition_Brief.ipynb
│   model.joblib
│   Rapport_reconnaissance_audio.pdf
│   README.md
│   scaler.joblib
│
├───Dataset
│       DataSet__{¯Ă__.csv
│
└───Tools
       beep-04.wav
       tools.py
       tools.py.bak

```

Dans ce projet on retrouve un *jupyter notebook* dans lequel ont été réalisées toutes les étapes du projet : 
1. Collecte du jeu de données (DataSet)
2. Traitement des données et test des différents modèles de classification
3. Application temps réel avec le meilleur modèle

Deux fichiers *.joblib* contenant le meilleur modèle de classification sélectionné, ainsi que le *StandardScaler* utilisé. Un succin rapport au format *pdf*, expliquant les différentes étapes de ce projet. Ainsi que deux dossiers (*DataSet*, *Tools*) dans lesquels on retrouve respectivement, le DataSet au format *csv*, et les scripts python qui nous ont été fournis pour la collecte des données et l'application en temps réel.