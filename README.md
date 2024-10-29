Tacotron - Génération d'Audio par Mot

###Description

Ce projet consiste en une modification du modèle Tacotron pour générer un fichier audio distinct pour chaque mot dans une phrase donnée. L'implémentation utilise les mécanismes d'attention internes du modèle Tacotron, sans aucun outil d'alignement externe, et utilise Griffin-Lim comme vocodeur.

###Fonctionnalités

Découpage par mot : Le modèle génère un fichier audio par mot pour une phrase spécifiée.
Vocodeur Griffin-Lim : Synthèse vocale réalisée avec Griffin-Lim, tel que fourni dans le projet.
Phrase test : La phrase utilisée pour la démonstration est "hello there i am modifying tacotron model and it's fun".

###Installation

Cloner le repository :
git clone https://github.com/SoroFereLaha/Modification-du-Modele-Tacotron-pour-la-Generation-d-Audio-par-Mot

Ouvrir le notebook Google Colab ou exécuter le code localement en installant les dépendances.

###Utilisation

Charger le modèle et le script de modification dans Google Colab.
Exécuter le notebook pour obtenir un fichier audio pour chaque mot de la phrase test.

###Contenu

Notebook : Le code et les explications se trouvent dans le fichier modified_tacotron.ipynb.
Exemples : Des exemples de sorties audio sont inclus dans le notebook.

###Auteurs
Projet réalisé par Soro Fêrêlaha
