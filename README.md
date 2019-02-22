# TP temps reel
TP temps réel à l'INSA sur le robot Dumber supervisé par une raspberry pi.

# Gestion du repo git
Les commandes nécéssaires pour travailler sont (par ordre d'utilisation) : 
## Initialisation
```bash
git clone https://github.com/dotsumae/TP-temps-reel.git #Recuperation de notre code
git submodule update --recursive --init #Recuperation du code source du TP
```

## Mise à jour
```bash
git pull #Mise a jour du notre code
git submodule update --recursive #Facultatif : mise a jour du code du TP
```

## Envoi du travail
NB : lors d'un commit, il faut sortir de Vim en entrant `Echap :wq Entrée`. Un message de commit doit répondre à "Ce commit va...". Un message vide annule le commit.

```bash
git add . #Ajout eventuel de nouveaux fichiers
git commit -a #Preparation du commit en ajoutant tous les fichiers modifiés, mais pas les nouveaux !
git push #Envoie tes modifications sur le repo en ligne.
```
NB 2 : En cas d'erreur lors du push, vérifie que tu a bien mis à jour le repo avant de commit.


# Guide du projet
Le guide pour commencer le projet avec Netbeans est hébergé sur [Moodle](https://moodle.insa-toulouse.fr/pluginfile.php/92209/mod_resource/content/6/guide.pdf).
