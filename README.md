# TP_Git_Python - Mon assistant de révision

## Présentation
Ce projet a été réalisé dans le cadre du TP - Outils Collaboratifs / Git / GitHub en Licence 1.
L'objectif est de créer un petit programme Python main.py qui sert d'assistant de révision. Il discute avec l'utilisateur dans le terminal pour l'aider à organiser sa session de révision.
Le fichier main.py est le seul fichier de code du projet.

## Évolution du programme - Versions V1 à V4

V1 - Message de bienvenue (en local)
Première version créée sur mon PC. Le programme affichait juste :
print("=== Mon assistant de revision ===")
print("Bienvenue dans le programme !")

V2 - Ajout du prénom + premier push
On a amélioré le programme pour demander le prénom avec input() :
nom = input("Quel est votre prenom ? ")
print(f"Bonjour {nom} ! Bon courage pour tes revisions.")
Ensuite on a fait le premier git push pour envoyer le code sur GitHub.

V3 - Ajout de la matière (sur GitHub + git pull)
La matière a été ajoutée directement sur GitHub. Puis on a récupéré avec git pull :
matiere = input("Quelle matiere revises-tu ? ")
print(f"Tu revises : {matiere}.")

V4 - Ajout de la durée (version finale)
On a ajouté la dernière question, version finale sur le PC, ensuite envoyée avec git push :
duree = input("Combien de minutes vas-tu reviser? ")
print(f"Objectif : reviser {matiere} pendant {duree} minutes.")
Au final, le programme demande : prénom, matière, durée.

## Code final V4 - mon main.py complet
print("=== Mon assistant de revision ===")
nom = input("Quel est votre prenom ? ")
print(f"Bonjour {nom} ! Bon courage pour tes revisions.")
matiere = input("Quelle matiere revises-tu ? ")
print(f"Tu revises : {matiere}.")
duree = input("Combien de minutes vas-tu reviser? ")
print(f"Objectif : reviser {matiere} pendant {duree} minutes.")

## Comment exécuter le programme
Outils nécessaires : Visual Studio Code, Python installé, Git

Lancement sans commande (dans VS Code) :
1. Ouvrir le dossier TP_Git_Python dans VS Code
2. Cliquer sur main.py
3. Cliquer sur le bouton Run Python File en haut à droite

Lancement avec commande (dans le terminal) :
py main.py

Exemple de ce qui se passe quand on lance :
=== Mon assistant de revision ===
Quel est votre prenom ? Awa
Bonjour Awa ! Bon courage pour tes revisions.
Quelle matiere revises-tu ? Git
Tu revises : Git.
Combien de minutes vas-tu reviser? 30
Objectif : reviser Git pendant 30 minutes.

## Commandes Git utilisées pendant le TP
- git init : pour créer le dépôt Git local dans le dossier TP_Git_Python.
- git add : pour préparer les fichiers (main.py) avant de les enregistrer.
- git commit : pour enregistrer une version du programme dans l'historique local.
- git push : pour envoyer nos versions V2 et V4 du PC vers GitHub.
- git pull : pour récupérer la version V3 qui était sur GitHub vers notre PC.

Auteur : Licence 1 - Outils Collaboratifs 2026 EMMANUEL DALI