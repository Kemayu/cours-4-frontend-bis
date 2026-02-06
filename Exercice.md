# Exercice

## Lancer le projet

[X] Forker le projet
[x] Installer les dépendances 
[x] Lancer le projet en mode dev et vérifier son fonctionnement 

## Creation d'un workflow

Créer un workflow github action qui :

[x] Run le linter
[x] Build le dossier de prod (Dossier dist)
[x] Recupère le dossier dist 
[x] Deploie les sources sur une Github page

## Tips

- Gerer les permissions de votre workflow dans les paramètres du projet.
- Activer Github pages dans les paramètres
- Utilisez `npm ci` pour l'installation des dependances (évite la mise à jour du fichier lock)
- dans `vite.config.js` utilisez le paramètre `base`pour specifier le chemin de vos fichiers sources
- Utiliser des [artifacts pour deployer la page](https://github.com/actions/upload-pages-artifact)

