# Predict-movie-ratings
Predict movie ratings using a big data from https://movielens.org/, we based on tow type of data videos (trailleres) and textual data.



The Notebooks description.


#AUDIO_PREPROCESSING.ipynb
- Extraction des audios en fichiers .wav
- Sauvegarde des dictionnaires contenant les identifiants des films et leur signal.
- Extraction des features audio


#AUDIO_MODELING.ipynb
- Entrainement avec plusieurs modèles 

#IMAGE_EXTRACTION.ipynb
-Fait l’extraction des Keyframes dans les vidéos selon le sens.
-Fait l’extraction des frames dans les vidéos selon la durée de vidéo.

#IMAGE_PREPROCESSING.ipynb
- Features engineering sur des Keyframes dans les vidéos.
- Features engineering sur des frames dans les vidéos selon la durée de vidéo.

#IMAGE_MODELING.ipynb
- Modeling  utilisant les features des Keyframes dans les vidéos.
- Modeling  utilisant les features des frames dans les vidéos selon la durée de vidéo.

#TEXTE_FINAL_PREPROCESS_&_MODEL&INTEGRATION.ipynb
-Fait le preprocessing texte
-Fait le modeling texte 
-Récupère les dataframes audio et image crée le modeling ML inter-modalités.
