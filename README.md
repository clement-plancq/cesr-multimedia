# Données multimédia : Python pour le traitement d’images et de données audio

Supports de cours pour le Master mention Humanités Numériques du [CESR](https://cesr.univ-tours.fr/)

## Évaluation

 - devoirs : 60%
 - devoir final : 40%

Vous me remettez des *scripts* sous forme de fichiers *.py, pas des notebooks

## Planning

Binder pour tous les supports : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks)

 - 08/11/2024 : 9h-12h N. Destouches
    - Introduction [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fintroduction.ipynb) 
    - Séance 1 : premiers pas avec Pydub [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fseance-1.ipynb)
    
 - 15/11/2024 : 9h-12h salle Rapin
	- Séance 2 : traitement d’images 1 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clement-plancq/cesr-multimedia/blob/main/notebooks/traitement-images-1.ipynb)
	- Exercice avec Pillow. Écrivez un script qui produit une vignette d’une image de taille 120 x 120, au format png.  


 - 22/11/2024 : 9h-11h salle Rapin
   - Séance 3 : Traitement d’images 2 [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clement-plancq/cesr-multimedia/blob/main/notebooks/traitement-images-2.ipynb)
   - Exercice. Réalisez une détection de contours sur une image que vous compresserez avec 3 niveaux qualité décroissante : 75, 40 et 15


 - 03/12/2024 : 16h-18h salle Margolin
   - Traitement d’images 3  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bxdVxK7Gs0aQxfXZEqtpBtCltPDCCuyD?usp=sharing) 
   
    - Exercice avec ultralytics. Sur l’image de votre choix, faîtes une détection d’objet et filtrez les résultats pour n’avoir que ceux qui 1. ont un score de confiance supérieure à 0.7 et 2. ont une catégorie 'Personne' ou animal (ou fruit comme vous préférez)
 
 - 11/12/2024 : 14h-17h 
   - IIIF [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-iiif.ipynb)

 - 13/12/2024 : 14h-17h salle Rapin

 - Devoir final : 
 
 Vous devrez combiner la détection d’objets et l’utilisation de l’API Image de IIF.

 Vous utiliserez Google Colab et vous remettrez votre fichier `ipynb` (Fichier > Télécharger > Télécharger le fichier .ipynb)

    1. Sélectionnez trois images accessibles via l’API Image de IIIF
    2. Mettez en œuvre la détection d’objets sur ces images à l’aide de la bibliothèque Ultralytics 
    3. Pour chaque image, relevez les coordonnées et la classe des deux objets détectés ayant les taux de confiance (*confidence score*) les plus élevés. Aidez-vous de la [documentation](https://docs.ultralytics.com/fr/modes/predict)
    4. À l’aide des coordonnées des objets détectés et de l’API Image IIIF, pour chaque objet composez l’url qui vous permettra de l’afficher. En couleur et en niveau de gris.