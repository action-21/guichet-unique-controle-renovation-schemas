# Guichet unique de contrôle de la rénovation - Schemas de données publiques

> [!NOTE]
> Ce dépôt fait partie du projet [Guichet unique de contrôle de la rénovation](https://github.com/action-21/guichet-unique-controle-renovation).

> [!IMPORTANT]
> Projet actuellement en cours de développement.

Schéma de données publique pour le déploiement d'un open data des contrôles de travaux de rénovation énergétique.

## Besoins couverts par l'open data

- Les données doivent permettre d'identifier les doublons lors de la publication de nouveux contrôles ;

- Les données doivent permettre d'identifier les éventuelles non conformités constatées par l'organisme de contrôle ;

- Les données doivent permettre d'évaluer la conformité d'une opération dans le cadre des dispositifs soumis à une obligation de contrôle ;

- Les données doivent permettre de suivre l'évolution de la qualité des travaux contrôlés ;

- Les données doivent permettre d'identifier l'organisme de contrôle responsable ;

- Les données doivent permettre une interopérabilité avec les sytèmes d'information.

## Description des données essentielles

- id: Identifiant unique du contrôle
- reference: Référence externe utilisée pour association
- remplace: Identifiant du contôle remplacé
- date_publication: Date de publication du contrôle dans l'open data
- rnb_id: Identifiant du bâtiment du Référentiel National des Bâtiments
- travaux: Nature des travaux contrôlés
- adresse: Adresse au format Base Adresse Nationale
- organisme_controle: Identification de l'organisme de contrôle
    - raison_sociale
    - siren
- non_conformites: Liste des non conformités constatées
    - type: Type de non conformité (mineur / majeur)
    - nature: Nature de la non conformité
