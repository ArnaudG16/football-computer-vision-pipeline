# Football Tactical Analysis Pipeline ⚽️📊

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![YOLOv8](https://img.shields.io/badge/YOLO-v8-green)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-red)

Ce projet implémente un pipeline complet de Computer Vision capable de transformer une vidéo de match de football brute en données tactiques exploitables (coordonnées 2D des joueurs sur une carte).

L'objectif est d'automatiser l'extraction de données de tracking à partir d'angles de caméra TV standards, sans capteurs GPS.

## Démo du tracking

![Aperçu du Tracking](demo.png)

## 🛠 Architecture du Pipeline

Le projet est découpé en 4 étapes :

1.  **Détection d'objets (`detection_objets_yolo.ipynb`)** :
2.  **Segmentation des Équipes (`clustering_equipes_kmeans.ipynb`)** :
3.  **Transformation de Perspective (`transformation_perspective_homographie.ipynb`)** :
4.  **Tracking & Pipeline Final (`pipeline_complet_tracking.ipynb`)** :


## 📦 Installation
```bash
pip install ultralytics opencv-python pandas scikit-learn matplotlib numpy yt-dlp
