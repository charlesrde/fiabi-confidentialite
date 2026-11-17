---
title: Politique de confidentialité de Fiabi
---

# Politique de confidentialité de Fiabi

Dernière mise à jour : 17 novembre 2026

Fiabi est une extension gratuite pour le navigateur Chrome. Elle vous aide à juger une boutique en ligne créée avec Shopify, en comparant ce que la boutique annonce à ce qui peut être vérifié. Cette page explique quelles données Fiabi utilise, où elles vont, et ce que Fiabi ne fait pas.

## En bref

- Fiabi n'a **ni compte, ni serveur, ni publicité, ni outil de mesure d'audience**.
- Fiabi **ne collecte aucune donnée sur vous**, et n'en vend ni n'en partage aucune.
- Fiabi ne lit une page **que lorsque vous cliquez sur son icône**.
- Deux informations sur la **boutique** analysée (jamais sur vous) sortent de votre navigateur, et seulement si l'option « vérifications externes » est activée. Elle l'est par défaut, et vous pouvez la couper dans l'onglet « Sources ».

## Ce que Fiabi lit

Quand vous cliquez sur l'icône, Fiabi lit la page de la boutique affichée dans l'onglet : son contenu, ses fichiers publics (catalogue de produits, conditions de vente, de livraison et de retour, page de contact, page « À propos ») et, si vous l'avez autorisé, le cadre d'un autre site qui affiche les avis de la boutique.

Cette lecture se fait **entièrement dans votre navigateur**. Rien de ce contenu n'est envoyé à un serveur de Fiabi : il n'y en a pas. Pour repérer les boutiques générées par intelligence artificielle, Fiabi examine les textes et les noms des images déjà lus : aucune image n'est téléchargée ni envoyée ailleurs.

## Ce qui sort de votre navigateur

Seulement si l'option « vérifications externes » est active, Fiabi interroge des services publics et gratuits. Il leur envoie uniquement :

| Donnée envoyée | Service | Pourquoi |
|---|---|---|
| Le **nom de domaine** de la boutique (par exemple boutique-exemple.fr) | rdap.org | Connaître l'âge de l'adresse du site |
| Le **nom de domaine** de la boutique | archive.org (archives du web) | Trouver la plus ancienne copie du site |
| Le **numéro SIREN** affiché par la boutique | recherche-entreprises.api.gouv.fr (État français) | Vérifier le nom et la situation de l'entreprise au registre |
| Le **numéro SIREN** affiché par la boutique | bodacc-datadila.opendatasoft.com (annonces légales officielles, BODACC) | Repérer une liquidation, une procédure collective ou une vente de l'entreprise |

Ces données concernent la **boutique**, pas vous. Fiabi n'envoie jamais votre identité, votre historique de navigation, vos autres onglets ni aucune information sur votre appareil. Les demandes sont faites sans cookie. Les adresses locales ou de test ne sont envoyées nulle part. Comme pour toute visite d'un site web, ces services voient l'adresse IP d'où vient la demande ; ils ont leur propre politique de confidentialité.

Les liens « Vérifier ailleurs » (Trustpilot, Scamadviser, Google, archives du web, Google Lens, TinEye, AliExpress, annuaire des entreprises) ne s'ouvrent que si vous cliquez dessus.

## Ce qui est gardé sur votre appareil

Fiabi utilise l'espace de stockage de votre navigateur, **uniquement sur votre appareil** :

- vos réglages (vérifications externes et mémoire des visites, activées ou non) ;
- un résultat temporaire par onglet, gardé 10 minutes, effacé à la fermeture de l'onglet ou du navigateur ;
- la **mémoire des visites**, que vous pouvez couper et effacer : pour chaque boutique analysée, la date, le score, le nom de la boutique, le temps restant d'un éventuel compte à rebours et la mention de stock affichée. Elle sert à repérer qu'un compte à rebours repart de zéro, qu'un stock « limité » ne bouge jamais ou qu'une boutique a changé de nom. 300 boutiques au plus. Ces données ne quittent jamais votre navigateur.

Couper la mémoire des visites dans l'onglet « Sources » efface aussitôt ce qui avait été gardé. Désinstaller l'extension efface tout le reste.

## Autorisations demandées

- **Lire l'onglet actif** (`activeTab` et `scripting`) : seulement après un clic sur l'icône de Fiabi.
- **Stockage** (`storage`) : garder vos réglages et la mémoire des visites sur votre appareil.
- **Autorisation facultative de lire un autre site**, par exemple le site d'un outil d'avis dont le cadre est affiché dans la boutique : Chrome vous la demande site par site, rien n'est demandé à l'installation, et vous pouvez la retirer à tout moment dans l'onglet « Sources ».

## Sécurité

Le texte venant d'une boutique est toujours affiché comme du simple texte, jamais exécuté. L'analyse tourne dans un espace isolé de l'extension, que les scripts de la boutique ne peuvent ni lire ni modifier. Aucun code n'est téléchargé depuis Internet : tout est dans l'extension.

## Enfants

Fiabi ne collecte aucune donnée personnelle, de personne.

## Changements

Si cette politique change, la date en haut de la page sera mise à jour. Toute nouvelle sortie de données serait annoncée dans la fiche de l'extension avant d'être activée.

## Contact

Une question sur vos données : **equipe.fiabi@gmail.com**
