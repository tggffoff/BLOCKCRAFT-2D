# Blockcraft 2D

Un clone 2D d'un jeu de survie en blocs, jouable directement dans le navigateur (desktop et mobile) — un seul fichier HTML, un monde procédural infini, et une sauvegarde cloud via Supabase.

> Prototype d'apprentissage personnel. Graphismes, code et contenu 100% originaux — non affilié à Mojang / Microsoft.

## ✨ Fonctionnalités

- **Monde procédural par seed** — 6 biomes (plaine, forêt, désert, montagne, neige, marais), cavernes, filons de minerai, arbres, **villages générés automatiquement**
- **Survie complète** — vie, faim, régénération, dégâts de chute, mort/réapparition
- **Minage & construction** — temps de minage selon l'outil et le matériau, aperçu de placement
- **Inventaire & crafting** — 36 emplacements, grilles de craft 2×2/3×3, four (fonte de minerai, cuisson), outils avec durabilité, catalogue créatif complet
- **Combat & IA** — mobs hostiles (zombie, araignée, squelette, slime) et passifs (vache, cochon, mouton, poulet) avec comportements distincts, apparition nocturne
- **Cycle jour/nuit** avec éclairage dynamique (soleil, torches, lave)
- **3 modes de jeu** — Survie, Créatif (vol libre, ressources illimitées), Spectateur
- **Contrôles adaptatifs** — clavier/souris sur desktop, joystick + boutons tactiles personnalisables sur mobile
- **Comptes joueurs & sauvegarde cloud** — inscription/connexion (Supabase Auth), sauvegarde automatique et manuelle, plusieurs mondes par compte

## 🛠️ Stack technique

- HTML5 Canvas + JavaScript vanilla (aucun framework, aucune dépendance de build)
- [Supabase](https://supabase.com) pour l'authentification et la persistance des sauvegardes (Postgres + RLS)
- Génération procédurale par bruit de valeur (seedable, déterministe)

## 🚀 Lancer le jeu

Aucune installation requise :

1. Clone ou télécharge le dépôt
2. Ouvre `index.html` dans un navigateur (ou héberge-le sur Netlify/Vercel/GitHub Pages)

Pour activer les comptes et la sauvegarde cloud, configure ton propre projet Supabase et remplace `SUPABASE_URL` / `SUPABASE_KEY` en haut du fichier.

## 🗺️ Roadmap

- [ ] Système de chunks/culling pour les grands mondes
- [ ] Squelette avec attaque à distance
- [ ] Structures supplémentaires (mines abandonnées, donjons avec loot)
- [ ] Musique et effets sonores
- [ ] Réassignation des touches

## 📄 Licence

Projet personnel — tous droits réservés à l'auteur sauf mention contraire.

---

Créé par **tggff_off**
