# OniXpress
![Langue](https://img.shields.io/badge/Langue-Français-blue.svg)
![Licence](https://img.shields.io/badge/licence-GPL--3.0-red?style=flat-square)
![GitHub Issues](https://img.shields.io/github/issues/Ax4M3/OniXpress?style=flat-square)

### Pour me retrouver et me soutenir
[![Blog](https://img.shields.io/badge/Blog-avecmodestie-007acc?style=flat-square&logo=wordpress)](https://avecmodestie.wordpress.com/)
[![Mastodon](https://img.shields.io/badge/Mastodon-Profil-563acc?style=flat-square&logo=mastodon)](https://piaille.fr/@Axm)
[![Liberapay](https://img.shields.io/badge/Liberapay-Faire_un_don-f6c915?style=flat-square&logo=liberapay&logoColor=black)](https://liberapay.com/AxM3/donate)

Générateur simplifié de notices de livres au format standard ONIX 3.0, pensé pour soutenir les éditeurs indépendants et la bibliodiversité.

**[Pour tester l'outil en ligne (GitHub Pages)](https://ax4m3.github.io/OniXpress/)**
---
## Utilisation

1. Allez directement sur le [GitHub Pages](https://ax4m3.github.io/OniXpress/).
2. Remplissez les métadonnées de votre livre dans le formulaire de gauche *(les champs obligatoires pour la chaîne du livre sont marqués d'un astérisque rouge*).*
3. Vérifiez et visualisez en temps réel le rendu de votre épreuve sur le panneau latéral droit *(ou en bas sur téléphone)*.
4. Cliquez sur **Télécharger le .xml** pour générer instantanément votre fichier au format standardisé `fiche-onix.xml` (ou nommé d'après votre ISBN).
5. Vous pouvez également cliquer sur **Copier le XML** pour copier directement le code XML généré dans votre presse-papiers.
6. Transmettez ou déposez simplement ce fichier XML sur l'espace professionnel de votre distributeur ou de vos plateformes de diffusion (Dilicom, Electre, etc.).

**Attention !** ce générateur produit un squelette ONIX 3.0 structurellement correct pour un cas simple. Il ne fait pas de validation XSD complète et la liste de classification est volontairement réduite. Vérifiez les codes auprès des listes officielles [EDItEUR](https://www.editeur.org/) avant envoi à un distributeur.

## Informations

- **Souveraineté & Sécurité :** OniXpress est une application purement statique de type *Client-Side*. Tout s’exécute localement à l’intérieur de votre propre navigateur web.
- **Zéro serveur, zéro stockage :** Aucune donnée saisie ne quitte jamais votre ordinateur et rien n'est enregistré sur un cloud externe. L'outil fonctionne même de manière totalement déconnectée d'Internet.
- **Accessibilité technique :** Développé bénévolement par un étudiant en Métiers du Livre et du Patrimoine pour mettre le code au service de la création culturelle, en libérant les éditeurs indépendants des fichiers structurés pouvant être complexes.

## Licence

Ce projet est distribué sous **licence GPL-3.0.** Voir le fichier [LICENSE](https://github.com/Ax4M3/OniXpress/blob/main/LICENSE) ou la page [licence.html](https://ax4m3.github.io/OniXpress/licence.html) pour plus de détails.
