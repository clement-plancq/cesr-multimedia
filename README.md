# Données multimédia : Python pour le traitement d’images et de données audio

Supports de cours pour le Master mention Humanités Numériques du [CESR](https://cesr.univ-tours.fr/)


## Présentation du cours

Ce cours propose une introduction pratique à la manipulation de données multimédia à l'aide de Python.  
Les étudiant·e·s apprendront à :

- Manipuler et analyser **données audio** et **images**
- Utiliser des bibliothèques Python spécialisées (Pydub, Pillow, Ultralytics)
- Exploiter l’API **IIIF Image** pour récupérer et afficher des ressources iconographiques en haute résolution
- Présenter leur travail sous forme de **notebook reproductible**

Les séances sont organisées sous forme de **travaux pratiques guidés** sur notebooks (Binder / Colab).  
Binder pour tous les supports : [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks)

## Planning

 - Vendredi 24/10 : 13h30-16h30, FR16
 - Lundi 03/11, 13h30-16h30, FR 16
 - Jeudi 13/11, 8h30-12h, TA 201
 - Jeudi 20/11, 13h30-16h30, salle Néricault Destouches
 - Lundi 24/11, 15h30-17h30, salle St-Martin
 - Lundi 01/12, 9h-12h, salle Rapin
 - Lundi 08/12, 9h-12h, salle Rapin

## Programme des séances

### 1. Introduction & Premiers pas audio
24/10/2025 — 13h30–16h30 (FR 16)

**Objectifs :**
- Se familiariser avec l’environnement de travail (Jupyter, Binder, Colab)
- Comprendre la représentation numérique du son
- Charger, découper, mixer et exporter de l’audio avec Pydub

**Ressources :**  
- Introduction  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fintroduction.ipynb)

- Premiers pas avec Pydub  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fpydub-1.ipynb)  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fpydub-2.ipynb)


### 2. Traitement d’images 1 — Manipulations de base  
03/11/2025 — 13h30–16h30 (FR 16)

**Objectifs :**
- Comprendre la structure d’une image (pixels, canaux, formats)
- Manipuler les images avec Pillow / NumPy
- Effectuer rotations, conversions, affichage comparatif

**Ressources :**
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-1.ipynb)  
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clement-plancq/cesr-multimedia/blob/main/notebooks/traitement-images-1.ipynb)

---

### 3. Traitement d’images 2 — Filtres et transformations  
13/11/2025 — 8h30–12h (TA 201)

**Objectifs :**
- Appliquer filtres (flou, netteté, débruitage)
- Modifier histogramme / contraste
- Effectuer seuillage et détection de bords

**Ressources :**
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-2.ipynb)  
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clement-plancq/cesr-multimedia/blob/main/notebooks/traitement-images-2.ipynb)

---

### 4. Traitement d’images 3 — Détection d’objets  
20/11/2025 — 13h30–16h30 (Néricault Destouches)

**Objectifs :**
- Comprendre le fonctionnement des modèles pré-entraînés Ultralytics
- Charger une image dans Colab
- Extraire les boîtes englobantes et les scores de confiance

**Ressource :**
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bxdVxK7Gs0aQxfXZEqtpBtCltPDCCuyD?usp=sharing)

---

### 5. IIIF
24/11/2025 — 15h30–17h30 (St-Martin)

**Objectifs :**
- Comprendre la logique de l’API IIIF Image
- Extraire une région d’image à partir de coordonnées
- Combiner détection d’objet & recadrage dynamique

**Ressources :**
- PDF : `notebooks-pdf/traitement-images-iiif.pdf`  
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-iiif.ipynb)

---

### 6. Traitement audio — Analyse & visualisation  
01/12/2025 — 9h–12h (salle Rapin)

**Objectifs :**
- Représentation spectrale (FFT, spectrogramme)
- Extraire, visualiser et comparer des segments audio

**Ressources :**
- PDF : `notebooks-pdf/traitement-audio.pdf`  
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement_audio.ipynb)

---

### 7. Présentation orale du devoir final  
08/12/2025 — 9h–12h (salle Rapin)

 Vous devrez combiner la détection d’objets et l’utilisation de l’API Image de IIF.

 Vous utiliserez Google Colab et vous remettrez votre fichier `ipynb` (Fichier > Télécharger > Télécharger le fichier .ipynb)

  1. Sélectionnez trois images accessibles via l’API Image de IIIF (voir [https://iiif.io/guides/finding_resources/](https://iiif.io/guides/finding_resources/))
  2. Mettez en œuvre la détection d’objets sur ces images à l’aide de la bibliothèque Ultralytics 
  3. Pour chaque image, relevez les coordonnées et la classe des deux objets détectés ayant les taux de confiance (*confidence score*) les plus élevés. Aidez-vous de la [documentation](https://docs.ultralytics.com/fr/modes/predict)
  4. À l’aide des coordonnées des objets détectés et de l’API Image IIIF, pour chaque objet composez l’url qui vous permettra de l’afficher. En couleur et en niveau de gris.

 Votre rendu doit s’appuyer sur un notebook qui comportera :
  - des explications sur votre démarche, où et comment vous trouvez les données, quelles difficultés vous avez rencontré et quelles solutions vous avez pu apporter /10
  - du code Python, n’oubliez pas de le commenter /8
  - la présentation des résultats /4
