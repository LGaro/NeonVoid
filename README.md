# Neon Void — Web Preview

Shoot'em up spatial néon, jouable directement dans le navigateur (mobile ou desktop). Fichier unique auto-contenu (`index.html`) : canvas 2D, audio synthétisé (WebAudio), sauvegarde locale (`localStorage`).

## Jouer

Ouvrir `index.html` dans un navigateur, ou servir le dossier statiquement (GitHub Pages, Netlify, etc.). Sur iPhone : ouvrir dans Safari puis **Partager → Sur l'écran d'accueil** pour une icône type app.

## Contenu

- Campagne : 30 missions sur 6 secteurs, boss tous les 5 niveaux, objectifs (survie / élimination), histoire (Kae Solari, VESTA, Le Null).
- Vague Infinie et Surcharge Neurale (variante avec modules aléatoires en cours de run).
- Atelier : améliorations permanentes (Crédits), modules de combat (Noyaux, monnaie rare obtenue en battant des boss, max 2 équipés en Campagne/Infinie), vaisseaux à débloquer (Crédits).
- Boutique : aperçu UX de monétisation (pub simulée, packs de Noyaux, retrait des pubs) — les achats réels ne sont pas implémentés ici, seulement l'interface.

## Développement

Fichier unique, pas de build. Éditer `index.html` puis recharger. Aucune dépendance externe hors Google Fonts (Orbitron / Rajdhani).

## Lien avec le projet Godot

Ce dépôt est la version web (prototypage/démo rapide) de Neon Void. Le projet complet pour l'App Store (Godot 4, iOS/macOS) vit séparément en local et n'est pas encore synchronisé avec ces changements.
