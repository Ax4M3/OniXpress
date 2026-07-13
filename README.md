# OniXpress — Générateur ONIX 3.0 simplifié

<div align="center">
  <img src="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' fill='%231A1A1A'/%3E%3Ctext x='50' y='68' font-size='60' text-anchor='middle' fill='%23D4A017' font-family='serif'%3EO%3C/text%3E%3C/svg%3E" width='80' alt="Logo OniXpress" />
  <p align="center">
    <strong>Un code au service de la création culturelle et de la bibliodiversité.</strong>
  </p>

  ![Langue](https://img.shields.io/badge/Langue-Français-blue.svg?style=flat-square)
  ![Licence](https://img.shields.io/badge/Licence-GPL--3.0-red?style=flat-square)
  [![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub_Pages-green.svg)](https://ax4m3.github.io/OniXpress/)
  ![GitHub Issues](https://img.shields.io/github/issues/Ax4M3/OniXpress?style=flat-square)
  ![Version](https://img.shields.io/badge/Version-v1.6.2-gold?style=flat-square)
  ![Contributions](https://img.shields.io/badge/contributions-welcome-brightgreen?style=flat-square)
</div>

---
**OniXpress** est un outil en ligne léger et open-source conçu pour aider les éditeurs indépendants et auto-édités à générer facilement leurs fiches de métadonnées de livres au format standard international **ONIX 3.0**. 

Il élimine la complexité de la manipulation directe des fichiers XML structurés en proposant un formulaire de saisie guidé.

**[Tester l'outil en direct sur GitHub Pages](https://ax4m3.github.io/OniXpress/)**

## Fonctionnalités clés

* **Formulaire guidé :** Saisie intuitive des informations indispensables de la chaîne du livre (Titre, ISBN, Prix, Contributeurs...).
* **Aperçu en temps réel :** Visualisez instantanément la structure du code XML généré sur le panneau latéral (ou en bas de page sur mobile).
* **Classification Thema :** Intégration d'un mini-navigateur de catégories Thema (liste étendue synchronisée) pour enrichir le champ *Subject*.
* **Actions rapides :** Copie du code XML en un clic dans le presse-papiers ou téléchargement direct du fichier `.xml` nommé d'après votre ISBN.
* **Souveraineté et sécurité totale :** Application purement statique (*Client-Side*). Vos données ne quittent **jamais** votre ordinateur et aucun serveur n'intervient. L'outil fonctionne même 100% hors-ligne.

## Technologies
* **Front-end :** HTML, JavaScript, CSS.
* **Architecture :** Application 100% statique (Client-side) garantissant une confidentialité totale.

## Comment l'utiliser ?

1. Rendez-vous sur [OniXpress en ligne](https://ax4m3.github.io/OniXpress/).
2. Remplissez les métadonnées de votre livre. Les champs obligatoires pour le bon traitement par les réseaux de distribution sont marqués d'un **astérisque rouge (`*`)**.
3. Vérifiez la validité de vos données grâce à l'aperçu dynamique.
4. Cliquez sur **Télécharger le .xml** ou **Copier le XML**.
5. Déposez ou transmettez simplement ce fichier sur les espaces professionnels de vos partenaires (Dilicom, Electre, distributeurs, etc.).

> ⚠️ **Attention :** Cet outil produit un squelette structurellement correct pour les cas de figures courants de l'édition. Il n'effectue pas de validation par schéma XSD complet et sa liste de genres est synthétique. Pensez à valider vos codes auprès des instances officielles de l'[EDItEUR](https://www.editeur.org/) avant vos envois de production.

## À propos et engagement

OniXpress a été développé bénévolement par un étudiant en *Métiers du Livre et du Patrimoine* afin de libérer les petites structures éditoriales des contraintes techniques de formats parfois complexes, rendant l'écosystème du livre plus accessible.

### Me retrouver et soutenir le projet
Si l'outil vous fait gagner du temps dans votre quotidien d'éditeur, vous pouvez soutenir mon travail :

[![Blog](https://img.shields.io/badge/Blog-avecmodestie-007acc?style=flat-square&logo=wordpress)](https://avecmodestie.wordpress.com/)
[![Mastodon](https://img.shields.io/badge/Mastodon-Profil-563acc?style=flat-square&logo=mastodon)](https://piaille.fr/@Axm)
[![Liberapay](https://img.shields.io/badge/Liberapay-M'offrir_un_café-f6c915?style=flat-square&logo=liberapay&logoColor=black)](https://liberapay.com/AxM3/donate)

## Contribuer
Les contributions sont bienvenues !
* **Signaler un bug :** Utilisez le [Rapport de bug](.github/ISSUE_TEMPLATE/bug_report.md).
* **Suggérer une amélioration :** Utilisez la [Demande d'amélioration](.github/ISSUE_TEMPLATE/feature_request.md).
* **Code de conduite :** Merci de respecter notre [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md).

## Citer l'outil
Si vous utilisez OniXpress dans le cadre de vos travaux ou de vos projets, vous pouvez nous citer via le fichier [CITATION.cff](CITATION.cff) présent à la racine du dépôt.

## Licence
Ce projet est un logiciel libre distribuable sous les termes de la licence **GPL-3.0**. Consultez le fichier [LICENSE](https://github.com/Ax4M3/OniXpress/blob/main/LICENSE) ou la page [license.html](https://ax4m3.github.io/OniXpress/pages/license.html) dédiée pour obtenir l'intégralité du texte juridique.