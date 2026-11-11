# Consignes de travail — AstroNote

La documentation produit de référence préparée pour ce dépôt est
[`docs/CONCEPT.md`](docs/CONCEPT.md) (vision et concept) et
[`docs/ROADMAP.md`](docs/ROADMAP.md) (périmètre et priorités). Consulter aussi le
README à la racine. Vérifier les chemins réels dans le dépôt avant toute
modification.

## Contexte produit connu

- Le modèle d’organisation retenu pour la bêta est **Espace → Sphère → Capsule**.
- Les Capsules confirmées pour la bêta sont **Todo**, **Agenda**,
  **Référentiel d’outils en ligne** et **WishList**.
- La WishList est une vue moodboard / Pinterest : les entrées ont un titre, des
  liens, des images et des détails, avec une image principale et des images
  secondaires ou alternatives.
- Le **suivi des prix est post-bêta**.
- Le dépôt est destiné initialement à un usage personnel ou à un petit groupe
  de testeurs.

La documentation préparée ne constitue pas un audit du code. Ne pas affirmer
qu’une fonctionnalité est implémentée sans l’avoir vérifiée dans le dépôt.
Les décisions techniques, les détails fonctionnels qui restent à spécifier et
les limites de la documentation sont signalés dans les documents de référence.

## Règles de travail

1. Inspecter l’état Git, les fichiers, les conventions, les scripts et les tests
   avant de proposer ou d’appliquer un changement.
2. Respecter le travail existant. Ne pas réinitialiser Git, supprimer ou
   réécrire massivement des fichiers.
3. Distinguer les décisions confirmées des questions ouvertes et de la vision
   post-bêta. Ne pas réintroduire la WishList comme fonctionnalité indécise ni
   inclure le suivi des prix dans le périmètre bêta.
4. Avant de choisir une pile ou une dépendance importante, comparer les options
   pertinentes selon la maintenabilité, la sécurité, l’accessibilité, le coût
   et l’adéquation au projet.
5. Traiter sécurité, confidentialité, permissions et migrations de données
   comme des exigences de conception.
6. Ne pas ajouter de secrets, identifiants ou données personnelles réelles.
7. Ne pas effectuer de commit ni de push sans demande explicite.
8. Vérifier réellement les changements et les commandes avant d’en rapporter
   les résultats. Signaler les ambiguïtés qui bloquent une décision.
