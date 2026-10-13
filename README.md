# Gatefall : Riposte

## Jouer

1. Télécharge le lanceur : **[Gatefall-Riposte-Lanceur.zip](https://github.com/DescartesEnigma/gatefall-riposte-jeu/raw/main/lanceur/Gatefall-Riposte-Lanceur.zip)** (38 Mo).
2. Clic droit sur le zip → **Extraire tout**. Tu obtiens un dossier « Gatefall Riposte ».
3. Dans ce dossier, lance **Gatefall Riposte - Lanceur.exe** : il télécharge le jeu (environ 900 Mo),
   puis le bouton **Jouer** s'allume. Aux mises à jour, il ne télécharge que ce qui a changé.

Windows peut afficher « Windows a protégé votre ordinateur » (le lanceur n'est pas signé) :
clique sur **Informations complémentaires** puis **Exécuter quand même**.

## Pour le lanceur (ne pas modifier à la main)

`manifest.json` décrit la dernière version, `morceaux/` contient le jeu découpé en morceaux de 24 Mo
nommés par leur sha256. Publié par `outils/publier_jeu.py`.
