# git_memoire
Détection Hiérarchique des Tumeurs Cutanées par IA

Projet de mémoire de Master 2 en Intelligence Artificielle, visant la détection précoce des tumeurs cutanées à partir d’images, à l’aide de modèles Deep Learning et d’une application mobile.

Objectif

Développer un système intelligent hiérarchique aligné sur la pratique clinique :

Niveau 1 : Tumeur vs Non-Tumeur

Niveau 2 : Tumeur Bénigne vs Maligne

Le système intègre une architecture CNN (EfficientNet-B7) et une approche CNN–Transformer, avec prise en compte des phototypes cutanés pour améliorer l’équité diagnostique.

 Méthodologie

Backbone : EfficientNet-B7 (ImageNet)

Architecture hiérarchique à deux niveaux

Modèle hybride CNN–Transformer au niveau critique (Malin/Bénin)

Pondération par classe et phototype

Scores de confiance interprétables

Déploiement

Backend : FastAPI (API d’inférence)

Mobile : Flutter (sélection/capture d’image, affichage clinique)

Communication mobile ↔ backend via API REST

 Résultats (résumé)

Niveau 1 : ~82% Accuracy (Tumeur / Non-Tumeur)

Niveau 2 : ~79% Accuracy (Malin / Bénin)

Amélioration du rappel des tumeurs malignes avec le Transformer

 Avertissement

Ce système est un outil d’aide à la décision et ne remplace pas un diagnostic médical professionnel.

 Auteur

Assane Ciss Diallo
Master 2 – Intelligence Artificielle
Université Iba Der Thiam de Thiès (UIDT)
