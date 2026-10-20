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

 - Mercredi 21/10 : 13h30-16h30, salle Néricault Destouches
 - Vendredi 13/11, 9h-12h, salle Rapin
 - Vendredi 20/11, 9h-12h30, salle Margolin
 - Lundi 23/11, 9h-12h, salle Rapin
 - Lundi 30/11, 14h-17h, salle Rapin
 - Vendredi 04/12, 9h-12h, salle Rapin
 - Lundi 07/12, 14h-16h salle Rapin

## Programme des séances

### 1. Introduction & Premiers pas en traitement d’image
21/10/2026

**Objectifs :**
- Se familiariser avec l’environnement de travail (Jupyter, Binder, Colab)
- Comprendre la structure d’une image (pixels, canaux, formats)
- Manipuler les images avec Pillow / NumPy
- Effectuer rotations, conversions, affichage comparatif

**Ressources :**  
- Introduction  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fintroduction.ipynb)
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-1.ipynb)  
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clement-plancq/cesr-multimedia/blob/main/notebooks/traitement-images-1.ipynb)


---

### 2. Traitement d’images 2 — Filtres et transformations  
13/11/2026

**Objectifs :**
- Appliquer filtres (flou, netteté, débruitage)
- Modifier histogramme / contraste
- Effectuer seuillage et détection de bords

**Ressources :**
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-2.ipynb)  
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clement-plancq/cesr-multimedia/blob/main/notebooks/traitement-images-2.ipynb)

---

### 3 et 4. Traitement d’images 3 — Détection d’objets  
20/11/2026 et 23/11/2026

**Objectifs :**
- Comprendre le fonctionnement des modèles pré-entraînés Ultralytics
- Charger une image dans Colab
- Extraire les boîtes englobantes et les scores de confiance

**Ressource :**
- [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bxdVxK7Gs0aQxfXZEqtpBtCltPDCCuyD?usp=sharing)

---

### 5. IIIF
30/11/2026

**Objectifs :**
- Comprendre la logique de l’API IIIF Image
- Extraire une région d’image à partir de coordonnées
- Combiner détection d’objet & recadrage dynamique

**Ressources :**
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement-images-iiif.ipynb)

---

### 6. Traitement audio — Analyse & visualisation  
04/12/2026

**Objectifs :**
- Comprendre la représentation numérique du son
- Charger, découper, mixer et exporter de l’audio avec Pydub
- Représentation spectrale (FFT, spectrogramme)
- Extraire, visualiser et comparer des segments audio

**Ressources :**
- Premiers pas avec Pydub  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fpydub-1.ipynb)  
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Fpydub-2.ipynb)
- PDF : `notebooks-pdf/traitement-audio.pdf`  
- [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/clement-plancq/cesr-multimedia/HEAD?labpath=notebooks%2Ftraitement_audio.ipynb)

---

### 7. Présentation orale du devoir final  
07/12/2026

 