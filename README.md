# Données multimédia : Python pour le traitement d’images et de données audio

Supports de cours pour le Master mention Humanités Numériques du [CESR](https://cesr.univ-tours.fr/)

## Évaluation

 - devoirs : 40%
 - projet : 60%

Vous me remettez des *scripts* sous forme de fichiers *.py, pas des notebooks

## Planning

 - 13/09/2023 : 9h-12h FR15
    - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fintroduction.ipynb) [introduction](notebooks-html/introduction.html)
    - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fseance-1.ipynb) [seance 1 : premiers pas avec Pydub](notebooks-html/seance-1.html)
    

 - 27/09/2023 : 10h30-12h30 CESR N. Destouches
     - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fseance-2.ipynb) [seance 2 : manipulations simples avec Pydub](notebooks-html/seance-2.html)
     - Exercices sur votre fichier audio (electric_cello.wav sinon)

        En utilisant le package Pydub et sa documentation :
        1. Amplifier de 12db les 6 premières secondes. Exporter le résultat dans un fichier wav
        2. Détecter les silences dans votre fichier. Afficher sur le nombre de silences et pour chacun les estampilles temporelles et la durée

        Vous me rendez un script (un fichier *.py) par question sur Celene.
      

 - 11/10/2023 : 9h30-11h30 FR15
     - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fseance-3.ipynb) [seance 3 : Analyses avec le package librosa](notebooks-html/seance-3.html)
     - Exercice sur la gamme de Do mineur. À l’aide de la documentation, obtenez les notes de la gamme de Do mineur (Cmin),
     obtenez les valeurs des notes en Hz et représentez cette gamme sur un spectrogramme (à l’aide de `librosa.feature.chroma_cqt`)

 - 08/11/2023 : 9h-12h CESR salle Margolin
     - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fseance-4.ipynb) [seance 4 : Traitement d’images 1](notebooks-html/seance-4.html)
     - Exercice avec Pillow. Écrivez un script qui à partir d’un lot de fichiers .jpg produit des vignettes de taille 120 x 120, en niveaux de gris, au format png.  
     Vous pouvez prendre par exemple les fichiers du dossier img sur le dépôt https://github.com/clement-plancq/cesr-multimedia qui se terminent par '1130x400.jpg'. Pensez à utiliser le module glob (https://docs.python.org/3/library/glob.html)

 - 15/11/2023 : 9h-12h CESR salle Margolin
     - [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fseance-5.ipynb) [seance 5 : Traitement d’images 2](notebooks-html/seance-5.html)
     - Exercice avec Pillow. Ajoutez un filigrane ('fine.jpg' ou autre chose si vous voulez) en bas à droite de chacune des trois images suivantes : CPR_1130x400.jpg, bunny.jpg, plane_1.jpg (les images sont sur le dépôt github)


 - 29/11/2023 : 9h-12h CESR N. Destouches
     - [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bxdVxK7Gs0aQxfXZEqtpBtCltPDCCuyD?usp=sharing) seance 6 : Traitement d’images (3), détection d’objets
     - Exercice avec ultralytics. Sur l’image de votre choix, faîtes une détection d’objet et filtrez les résultats pour n’avoir que ceux qui 1. ont un score de confiance supérieure à 0.7 et 2. ont une catégorie 'Personne' ou animal (ou fruit comme vous préférez)

 - 06/12/2023 : 9h-12h CESR salle Rapin
     - seance 7 : IIIF
 - 13/12/2023 : 9h-11h CESR salle Margolin
     - seance 8 : TP sur le projet

Binder pour tous les supports : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks)

