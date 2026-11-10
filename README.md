# AstroNote

> Nom de travail — susceptible d’évoluer.

Application personnelle multiplateforme conçue pour organiser différents aspects de sa vie dans un espace personnalisable, modulaire et sécurisé.

## Vision

AstroNote vise à réunir, dans une seule application, des outils d’organisation et de suivi : tâches, agenda, ressources en ligne, projets, budget, galerie et partage.

Chaque personne peut composer une organisation qui correspond à ses besoins, sans être submergée par les informations provenant d’autres domaines.

## Organisation de l’application

La structure retenue pour la bêta est :

**Espace → Sphère → Capsule**

- **Espace** : grand contexte, par exemple personnel, professionnel ou associatif.
- **Sphère** : domaine ou projet au sein d’un Espace, par exemple carrière, vacances ou couture.
- **Capsule** : unité fonctionnelle ou contenu organisé dans une Sphère.

Les informations pourront être consultées à différents niveaux, selon le contexte et les droits d’accès.

## Principes du projet

- **Personnalisation progressive** : commencer par une expérience simple, puis introduire davantage de personnalisation.
- **Modularité** : développer des fonctionnalités indépendantes, capables de s’intégrer entre elles.
- **Clarté** : faciliter le rangement et la recherche de l’information.
- **Sécurité et confidentialité** : limiter les accès et protéger les données.
- **Maintenabilité** : privilégier une architecture documentée, testable et évolutive.
- **Expérience multiplateforme** : viser le mobile, le bureau et le web.
- **Ouverture** : privilégier les outils et intégrations open source lorsqu’ils répondent aux besoins.

## Périmètre envisagé pour la bêta

Les fonctionnalités retenues ou envisagées pour la première version comprennent :

- création et organisation des Espaces, Sphères et Capsules ;
- gestion de tâches avec affichage en liste et/ou en kanban ;
- agenda ;
- liste de souhaits ;
- bibliothèque de ressources web avec tags et statuts, par exemple « favori », « utilisé fréquemment » ou « à tester » ;
- personnalisation initiale des espaces et de leur affichage ;
- premières bases du partage et des droits d’accès.

Le périmètre précis sera suivi dans [`docs/ROADMAP.md`](docs/ROADMAP.md).

## Vision à plus long terme

Les pistes envisagées, sans engagement pour la bêta, incluent notamment :

- budget et suivi financier ;
- galerie et gestion de médias ;
- partage avancé et gestion fine des droits ;
- intégrations avec des services tiers ;
- nouveaux modules développés par le projet ou ajoutés sous forme d’extensions ;
- tableaux de bord et widgets personnalisables ;
- vues transversales permettant de consulter des informations issues de plusieurs Sphères ou Espaces.

La vision détaillée est dans [`docs/CONCEPT.md`](docs/CONCEPT.md).

## État du projet

**Phase : cadrage et initialisation.**

La stack technique, l’architecture et les premières conventions de développement restent à définir. Les instructions d’installation et d’exécution seront ajoutées une fois le socle technique choisi.

## Sécurité

Ne commitez jamais de mots de passe, clés API, jetons d’accès ou données personnelles réelles.

Pour signaler un problème de sécurité, consultez [`SECURITY.md`](SECURITY.md). Pour l’instant, le projet est privé et destiné à un usage personnel ou à un petit groupe de testeurs.

## Licence et visibilité

Ce dépôt est actuellement privé. Aucun fichier de licence n’est fourni à ce stade.

## Langues

L’interface doit être disponible en français et en anglais dès la bêta.
L’architecture devra permettre d’ajouter d’autres langues ultérieurement,
sans intégrer les textes d’interface directement dans le code.

## Documentation

- [Concept et vision](docs/CONCEPT.md)
- [Roadmap](docs/ROADMAP.md)
- [Politique de sécurité](SECURITY.md)
