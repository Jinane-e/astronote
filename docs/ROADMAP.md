# Roadmap produit AstroNote

> Brouillon de mise à jour documentaire. Les priorités sont exprimées sans
> calendrier : aucun jalon ni ordre de livraison plus précis n’a été confirmé.
> Le contenu décrit le périmètre souhaité, pas l’état d’implémentation.

## Modèle bêta

**Espace → Sphère → Capsule**

- **Espace** : grand contexte.
- **Sphère** : sujet ou domaine dans un Espace.
- **Capsule** : unité fonctionnelle rattachée à une Sphère.

## Périmètre confirmé pour la bêta

### 1. Socle d’organisation

- Créer et consulter des Espaces, des Sphères et des Capsules.
- Naviguer entre ces niveaux en conservant un contexte compréhensible.
- Définir les frontières de données et les contrôles d’accès avant de permettre
  le partage. Le détail des rôles et de l’héritage des permissions reste à
  spécifier.

### 2. Capsules

#### Todo

Capsule de gestion de tâches. Les champs, états, filtres et présentation (liste,
kanban ou autre) ne sont pas définis dans les éléments disponibles.

#### Agenda

Capsule d’organisation d’éléments planifiés. Les vues, récurrences, rappels et
intégrations éventuelles restent à spécifier.

#### Référentiel d’outils en ligne

Capsule pour enregistrer et retrouver des sites ou outils en ligne. Les champs,
classement et statuts détaillés sont à confirmer avant implémentation.

#### WishList — confirmée pour la bêta

Capsule de souhaits présentée comme un **moodboard / tableau d’inspiration de
type Pinterest**. Une entrée comprend les éléments suivants, selon la demande
produit confirmée :

- un titre ;
- un ou plusieurs liens ;
- une ou plusieurs images, avec une image principale et des images secondaires
  ou alternatives ;
- des détails associés.

Le mode d’affichage souhaité est visuel et orienté moodboard. La présence de
la WishList dans le périmètre bêta est arrêtée ; seuls les comportements précis
(restauration, tri, collections, champs obligatoires, limites de liens/images,
stockage ou provenance des images, partage) restent à spécifier ; ils ne sont
pas supposés ici.

**Suivi des prix : post-bêta.** Ne pas l’inclure dans les tâches ou critères de
livraison bêta, ni supposer une collecte automatique de prix.

## Travail de cadrage restant

- Décrire les parcours principaux et les critères d’acceptation pour chaque
  Capsule, notamment l’ajout, la consultation et la modification d’une entrée
  WishList.
- Définir les champs et règles de validation de Todo, Agenda et du Référentiel.
- Pour la WishList, préciser les règles de gestion des images et des liens sans
  élargir implicitement le périmètre au suivi de prix.
- Spécifier l’authentification, le partage et les permissions nécessaires à la
  bêta, ou confirmer explicitement les limites de la première version.
- Choisir la stack et l’architecture après examen du dépôt et comparaison des
  options pertinentes.
- Définir sauvegarde, export, suppression, sécurité, tests et critères de sortie.

## Après la bêta — hors périmètre bêta confirmé

- Suivi des prix de la WishList.
- Fonctionnalités plus avancées, intégrations ou automatisations, sous réserve
  d’une décision ultérieure.
- Les autres pistes à long terme décrites dans le concept ne constituent pas un
  engagement de livraison.

## Validation de la bêta

Les critères de sortie restent à décider. À établir notamment : parcours
fonctionnels de bout en bout pour les Capsules retenues, tests des frontières
de données et des permissions, vérifications de sécurité et de qualité, et
documentation d’installation et d’utilisation correspondant effectivement au
projet.

## Limites de cette mise à jour

Les fichiers et l’historique du dépôt n’ont pas été audités : l’état du code,
les tâches achevées, la configuration, les tests, les dépendances et le statut
de chaque fonctionnalité sont invérifiables ici. Cette roadmap est un brouillon
prêt à intégrer et à confronter au dépôt, non un relevé d’avancement.
