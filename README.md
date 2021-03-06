# BackupLinux

### Script minimaliste et commenté de sauvegarde récursive et incrémentale des données utilisateur sous Linux (script de type "Bash").

* Effacement dans la sauvegarde des données supprimées dans la source mais copie conservée dans un répertoire spécial de la sauvegarde, en cas de besoin ou de fausse manipulation.

* Liste configurable de répertoires à exclure de la sauvegarde (caches, historiques de navigateurs, temporaires...)

* Configuration de Bash en mode "strict" (debogage facilité).

* Ne génère pas d'erreur lorsque la cible de sauvegarde ne supporte pas les droits Unix (ec. Disque externe formatté en FAT).

* Lancement depuis le bureau, en interface graphique (double-clic/icône).

* Cet outil comporte un "lanceur" qui ouvre une fenêtre console temporaire permettant d'exécuter le "backup" proprement dit et de s'assurer de son bon déroulement.

* Configurer la source de la sauvegarde, sa destination ainsi que les fichiers et répertoires à exclure éventuellement dans le script avant son 1er lancement.

* Testé sous Linux OpenSuse Leap - bureau KDE.

---
_Ces scripts, volontairement "sur-commentés", s'adressent aux débutants en scripting Bash._

_© Henri 10/12/19 - Plus d'informations : https://henri.nitnoc.me_
