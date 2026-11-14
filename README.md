# TP1 

## Présentation

 L'objectif de ce programme est d'aider un étudiant à préparer sa session d'étude en recueillant quelques informations simples.

Le fichier principal `main.py` permet d'interagir avec l'utilisateur dans le terminal et d'afficher un récapitulatif personnalisé de sa séance de révision.

## Versions V1 à V4

Le programme `main.py` a été développé en quatre étapes successives pour pratiquer le suivi de version :

* **Version 1 (V1)** : Création du fichier sur mon ordinateur avec l'affichage d'un premier message de bienvenue.
* **Version 2 (V2)** : Ajout de la demande du prénom de l'utilisateur en local, suivi du premier envoi (`push`) vers GitHub.
* **Version 3 (V3)** : Modification directe du code sur GitHub pour demander la matière à réviser, puis récupération de cette nouveauté sur mon PC avec `git pull`.
* **Version 4 (V4)** : Ajout de la saisie de la durée de révision (en minutes) sur mon ordinateur, suivi d'un dernier `git push` pour mettre à jour GitHub.

## Comment exécuter le programme

### Outils nécessaires
Pour utiliser ce programme, il faut avoir installé sur son ordinateur :
* **Python 3**
* **Visual Studio Code** (avec l'extension Python)

### Étapes de lancement
Pour démarrer le programme directement depuis VS Code :

1. Ouvrir le dossier `TP_Git_Python` dans VS Code, puis cliquer sur le fichier `main.py`.
2. Cliquer sur le bouton **▶ Run Python File** en haut à droite de l'éditeur (choisir l'interpréteur Python si demandé).
3. Dans le terminal intégré qui s'ouvre en bas, saisir successivement :
   * Le **prénom**
   * La **matière** à réviser
   * La **durée** de révision en minutes
4. Valider chaque réponse en appuyant sur la touche **Entrée**.

## Commandes Git utilisées

Voici le rôle des principales commandes Git utilisées lors de la réalisation du TP1 :

* `git init` : A permis de créer et d'initialiser un dépôt Git local dans le dossier du projet.
* `git add` : A servi à sélectionner et préparer les modifications du fichier `main.py` avant de les enregistrer.
* `git commit` : A permis de sauvegarder une version du projet dans l'historique local avec un message explicatif.
* `git push` : A servi à envoyer les sauvegardes locales vers le dépôt en ligne sur GitHub.
* `git pull` : A permis de récupérer sur mon ordinateur les modifications faites directement sur GitHub .
