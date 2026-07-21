# Guide de contribution à KartoLibr

Un grand merci pour l'intérêt que vous portez à **KartoLibr** ! Que vous soyez développeur, éditrice, éditeur ou spécialiste des métadonnées du livre, votre aide est précieuse pour faire vivre la bibliodiversité et l'édition indépendante.

Ce document rassemble quelques lignes directrices simples pour faciliter vos contributions.

---

## Comment pouvez-vous aider ?

Il y a plein de façons de participer au projet, même sans coder :
* **Signaler des bugs :** Ouvrez une *Issue* si le XML généré présente une anomalie ou si un distributeur rejette votre fichier.
* **Proposer des améliorations :** Ajout de nouvelles balises de la norme ONIX 3.0, gestion des sous-catégories Thema, etc.
* **Améliorer la documentation :** Clarifier les descriptions de l'aide ou corriger des fautes de frappe.
* **Faire des retours d'expérience :** Partager comment l'outil s'intègre dans votre quotidien d'éditeur indépendant.

---

## Développer localement

L'un des grands avantages d'KartoLibr est son architecture **100 % statique**. Vous n'avez pas besoin d'installer Node.js, Docker ou des dépendances complexes.

1. **Forkez** le dépôt sur votre compte GitHub.
2. **Clonez** votre fork localement :
   ```bash
   git clone https://github.com/Ax4M3/KartoLibr.git
3. Ouvrez simplement le fichier index.html dans le navigateur de votre choix pour voir l'application tourner en direct.
4. Modifiez le code avec votre éditeur de texte favori.

---

## Soumettre une Pull Request

Pour que votre contribution soit intégrée le plus sereinement possible, merci de respecter ces quelques points :

1. Restez léger (KISS — *Keep It Simple, Stupid*) : L'outil doit rester accessible et s'exécuter entièrement côté client (Client-Side). Évitez l'ajout de frameworks ou de bibliothèques lourdes qui casseraient la philosophie mono-page statique de l'application.
2. Évitez de modifier les numéros de version : Laissez moi le soin de mettre à jour le numéro de version (ex: v1.6.2) dans le `README` et l'interface lors du déploiement officiel.
3. Documentez votre modification : Dans la description de votre Pull Request, expliquez brièvement quel problème vous réglez ou quelle balise ONIX vous ajoutez (avec si possible un exemple de cas d'usage éditorial).

---

## Code de conduite

En participant à ce projet, vous vous engagez à maintenir un environnement bienveillant, respectueux et constructif pour l'ensemble des contributrices et contributeurs, quel que soit leur niveau technique ou leur expérience dans le monde du livre.

Merci encore pour votre soutien au logiciel libre et à l'édition indépendante !