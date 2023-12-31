﻿# LyNassTest

Dashboard Dash application which displays randomly one out of twenty course questions. You can evaluate answer to check if the answer matches perfectly or if it contains the keywords. You can also get another random question. The server is hosted on a AWS Linux virtual machine.

## Production

- AWS URL: http://13.50.245.140/ or http://ec2-13-50-245-140.eu-north-1.compute.amazonaws.com

## Usage


* Clone this repository, from your local machine:
  ```bash
  git clone https://github.com/LynaMOSTEFACHAA/LynaMOSTEFACHAA-Python-Git-Linux-Rattrapage.git
  ```
* Get the requirements
  ```bash
  # Install requirements with pip
  pip install -r requirements.txt
  #or just pip install every import e.g. dash:
  pip install dash
  ```

* Start the application (adapt the following path or go to your cloned directory)
  ```bash
  $ sudo python3 CourseTest.py
  ```
  or
    ```bash
  $ nohup python3 CourseTest.py &
  ```

* Important: If you use it locally, do not forget to adapt all paths in the application CourseTest.

### Questions and answers

- Quelle commande Git permet de voir l'historique des commits ?
  - Réponse: `git log`

- Comment changer l'auteur et l'adresse e-mail d'un commit en Git ?
  - Réponse: `git commit --amend --author='Auteur <email>'`

- Comment supprimer une branche locale en Git ?
  - Réponse: `git branch -d nom_de_la_branche`

- Comment résoudre les conflits de fusion en Git ?
  - Réponse: `Éditez manuellement les fichiers en conflit, puis utilisez 'git add' et 'git commit' pour valider les modifications.`

- Quelle commande permet d'afficher l'état du dépôt Git local par rapport au dépôt distant ?
  - Réponse: `git status`

- Comment mettre à jour un dépôt distant avec les modifications locales en Git ?
  - Réponse: `git push`

- Quelle est la commande pour créer un alias dans Git ?
  - Réponse: `git config --global alias.nom_alias 'commande'`

- Comment rechercher un commit spécifique dans l'historique des commits en Git ?
  - Réponse: `git log --grep='texte_du_commit'`

- Comment changer le message d'un commit déjà poussé sur le dépôt distant en Git ?
  - Réponse: `Utilisez 'git commit --amend', puis 'git push --force' pour forcer la mise à jour.`

- Quelle commande permet de compresser l'historique des commits en Git ?
  - Réponse: `git rebase -i`

- Comment créer un nouvel utilisateur dans Linux ?
  - Réponse: `sudo adduser nom_utilisateur`

- Quelle commande permet de redémarrer un service dans Linux ?
  - Réponse: `sudo systemctl restart nom_du_service`

- Comment afficher les informations système dans Linux ?
  - Réponse: `uname -a`

- Quelle commande permet de supprimer un dossier et son contenu dans Linux ?
  - Réponse: `rm -r dossier`

- Comment créer un nouveau répertoire dans Linux ?
  - Réponse: `mkdir nom_du_dossier`

- Comment copier un fichier ou un dossier dans Linux ?
  - Réponse: `cp source destination`

- Quelle commande permet de déplacer un fichier ou un dossier dans Linux ?
  - Réponse: `mv source destination`

- Comment rechercher des fichiers par nom dans Linux ?
  - Réponse: `find /chemin/du/dossier -name nom_du_fichier`

- Comment compter le nombre de lignes, de mots et de caractères d'un fichier dans Linux ?
  - Réponse: `wc fichier`

- Comment mettre à jour les paquets installés sur une distribution Linux basée sur Debian ?
  - Réponse: `sudo apt update && sudo apt upgrade`

## Author

- Nassim AILALI: nassim.ailali@edu.ece.fr
- Lyna MOSTEFA CHAA: lyna.mostefa_chaa@edu.devinci.fr


## 📚​ Documentation

Dash: https://dash.plotly.com

Python libraries: https://docs.python.org/fr/3/library/
