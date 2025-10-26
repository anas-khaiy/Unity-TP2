# Jeu de Tri des Déchets

## Lien Projet

https://drive.google.com/file/d/1QP_klNpKrrEjXkGQQjN3QKvAbSHynPcu/view?usp=share_link

## Introduction

Le projet consiste à créer un mini-jeu éducatif sur le tri des déchets. L’objectif est de sensibiliser les joueurs aux bonnes pratiques de recyclage en leur faisant trier différents types de déchets dans les poubelles correspondantes : nourriture, métaux et plastiques.
Le jeu utilise le moteur Unity et différents concepts de programmation et d’organisation de scène, notamment :

- Tags : pour identifier les objets selon leur catégorie (nourriture, métal, plastique).

- Box Collider avec trigger : pour détecter quand un objet entre dans une poubelle.

- UI (Interface Utilisateur) : pour fournir des boutons de contrôle et des panneaux d’information (recharge, consignes, victoire).



## Étapes du projet

## 1. Collecte et importation des assets

- Rechercher sur Unity Asset Store les objets nécessaires pour le jeu : déchets (nourriture, métaux, plastiques) et poubelles correspondantes.

- Importer tous les assets dans Unity.

- Importer le package DOTween pour faciliter le redimensionnement et l’animation des objets.

## 2. Placement et organisation des objets

- Placer tous les objets dans la scène Unity.

- Affecter des tags à chaque objet selon sa catégorie : Food, Metal, Plastic.

- Disposer les poubelles à des positions fixes dans la scène.

<img width="3420" height="1974" alt="image" src="https://github.com/user-attachments/assets/f47bda1a-d1c8-4218-a1c9-2c3c6477757b" />

## 3. Création du GameController

- Créer un script GameController pour gérer la logique du jeu.

- Ce script permet de drag and drop les objets vers les poubelles correspondantes.

<img width="3414" height="1972" alt="image" src="https://github.com/user-attachments/assets/b067a657-0c67-4952-971a-e89f0aa2e17f" />


## 4. Configuration des poubelles

- Chaque poubelle a un script attaché et un Box Collider configuré comme trigger.

- Les scripts vérifient si l’objet déposé correspond à la catégorie de la poubelle.

<img width="3420" height="2006" alt="image" src="https://github.com/user-attachments/assets/ccc34ff8-eb4d-447a-8ede-64f710690c53" />


## 5. Création de l’interface utilisateur (UI)

- Ajouter un bouton Recharger pour remettre le jeu à zéro.

- Ajouter un panneau Consignes pour expliquer le fonctionnement du jeu.

- Ajouter un panneau Victoire qui apparaît lorsque tous les objets sont correctement triés.

<img width="3414" height="1950" alt="image" src="https://github.com/user-attachments/assets/04a6beaf-ff63-4559-b72c-08c70f1aaa7c" />


## 6. Test et finalisation

- Vérifier que tous les objets peuvent être déplacés correctement.

- Vérifier que le tri est bien reconnu par les scripts des poubelles.

- Tester les boutons UI et l’affichage des panneaux.

<img width="3414" height="1986" alt="image" src="https://github.com/user-attachments/assets/fe7604f3-05b5-401e-8699-f7e413dcb38d" />



Youtube Demo : https://youtu.be/wk8JR5bdmG0











