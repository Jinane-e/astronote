# AstroNote — concept et vision

> Nom de travail provisoire. Ce document distingue la structure et le périmètre
> de bêta confirmés de la vision à plus long terme.

## Intention

AstroNote est conçu comme un compagnon personnel et collaboratif pour organiser
des sujets de vie et d’activité dans des contextes distincts. Le produit vise
initialement un usage personnel ou un petit groupe de testeurs. La confidentialité,
la clarté et une personnalisation progressive sont des principes directeurs.

## Modèle d’organisation retenu pour la bêta

**Espace → Sphère → Capsule**

- **Espace** : contexte de premier niveau (par exemple personnel ou
  professionnel).
- **Sphère** : domaine, sujet ou projet organisé au sein d’un Espace.
- **Capsule** : unité fonctionnelle rattachée à une Sphère.

Les règles précises de partage, d’agrégation et de permissions ne sont pas
établies par les informations disponibles et ne doivent pas être présumées.

## Périmètre bêta

Les Capsules confirmées pour la bêta sont **Todo**, **Agenda**, **Référentiel
d’outils en ligne** et **WishList**. Les détails fonctionnels de ces modules,
à l’exception des caractéristiques de WishList indiquées ci-dessous, restent
à préciser.

### WishList

La WishList est un tableau visuel de souhaits, avec une présentation de type
moodboard / Pinterest. Les entrées comprennent un titre, des liens, des images
et des détails. La présentation distingue une image principale et des images
secondaires ou alternatives.

Le **suivi des prix est post-bêta**. Aucune surveillance automatique, source de
prix, devise, historique ou alerte de prix n’est implicitement promise par cette
description. La manière de stocker, charger ou valider les images et les liens
reste à concevoir.

## Vision à plus long terme

La vision peut évoluer vers des fonctionnalités telles que le mode Focus,
des vues transversales, une personnalisation étendue, des galeries, des
intégrations ou extensions, ainsi que des fonctions de partage plus élaborées.
Le suivi des prix de la WishList relève également de l’après-bêta. Ces idées ne
sont pas des engagements pour la bêta.

## Principes de conception

- **Contexte maîtrisé :** présenter les informations dans leur Espace et leur
  Sphère afin de réduire le bruit.
- **Progressivité :** commencer par des parcours simples et ajouter des options
  sur la base de besoins confirmés.
- **Modularité :** séparer les responsabilités des Capsules sans présumer d’un
  système d’extensions déjà décidé.
- **Confidentialité et sécurité :** appliquer le moindre privilège et définir
  les frontières de données avant le partage.
- **Maintenabilité :** documenter les décisions techniques et vérifier le
  comportement par des tests adaptés.

## Décisions non établies par les informations reçues

La stack, l’architecture détaillée, les plateformes de lancement, le mode
d’authentification, les rôles de partage, les règles de synchronisation,
l’hébergement, la licence, le nom final et les contraintes techniques des
médias ne sont pas validés dans cette mise à jour.

## Portée et statut de ce document

Ce brouillon est préparé à partir des fichiers Markdown fournis et des décisions
produit du contexte récent. Le dépôt lui-même et son état de développement
n’ont pas été consultés ; ce document ne décrit donc pas des fonctionnalités
comme déjà implémentées.
