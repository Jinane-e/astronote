# Roadmap produit

> Roadmap initiale. Les priorités et le périmètre pourront changer à partir
> des retours des premiers utilisateurs.

## Phase 0 — Cadrage et fondations

- Confirmer les scénarios principaux de la bêta.
- Définir les utilisateurs, les données et les risques de sécurité.
- Choisir la pile technique après comparaison documentée des options.
- Définir architecture, stratégie de tests et conventions Git.
- Mettre en place dépôt, CI, documentation et environnements.

## Phase 1 — Socle de la bêta

- Créer et consulter des Espaces.
- Créer et consulter des Sphères dans un Espace.
- Ajouter et organiser des Capsules dans une Sphère.
- Assurer une navigation claire entre les niveaux.
- Séparer les données par Espace côté interface et côté autorisations.
- Créer une interface responsive et cohérente sur les plateformes retenues.

## Phase 2 — Capsules bêta retenues

### Todo
- Gérer des tâches sous forme de liste.
- Étudier ou intégrer une vue Kanban si elle reste raisonnable pour la bêta.
- Définir les propriétés minimales des tâches et leur rattachement au contexte.

### Agenda
- Consulter et organiser des événements ou éléments planifiés.
- Préciser les vues, rappels, récurrences et éventuelles intégrations avant
  d’engager leur développement.

### Référentiel d’outils en ligne
- Enregistrer une URL et les informations utiles associées.
- Classer avec des tags.
- Marquer comme favori ou usage fréquent.
- Ajouter un statut « à tester ».
- Retrouver les outils depuis les Sphères pertinentes.
- Définir si une même entrée peut être associée à plusieurs Sphères.

### WishList
- Une liste orientée WishList a été préférée à un module de notes trop général.
- **À confirmer comme élément ferme du périmètre bêta** : sa présence a été
  évoquée, mais n’a pas encore été arrêtée avec le même degré de précision que
  Todo, Agenda et le Référentiel.

## Phase 3 — Validation et finition bêta

- Ajouter des tests aux parcours principaux et aux frontières de permissions.
- Vérifier accessibilité, ergonomie clavier et affichage mobile.
- Tester sauvegarde, restauration, export et suppression selon les décisions
  prises au cadrage.
- Corriger les défauts bloquants et documenter les limites connues.
- Inviter un petit groupe de testeurs et recueillir leurs retours.
- Ajuster priorités et expérience selon les usages observés.

## Vision post-bêta — non incluse par défaut

- Mode Focus.
- Partage avancé et gestion complète des droits.
- Personnalisation étendue des portails, widgets et thèmes.
- Agrégations de données entre Sphères et au niveau d’un Espace.
- Galerie et gestion de contenus plus riche.
- Comptes, coffre-fort et gestion de mots de passe.
- Budgétisation et fonctionnalités financières.
- Notes structurées, si leur rôle est distinct des autres Capsules.
- Extensions et intégrations tierces.
- Écosystème de Capsules plus ouvert.

## Critères de sortie de bêta

À préciser avant la mise à disposition. Proposition initiale :

- Les utilisateurs pilotes peuvent créer et retrouver leurs Espaces, Sphères et
  Capsules sans aide.
- Les parcours des Capsules retenues fonctionnent de bout en bout.
- Les frontières entre Espaces et les permissions sont testées.
- Les défauts critiques de sécurité et de données sont corrigés.
- La documentation d’installation, d’utilisation et de contribution est à jour.
- Les limites connues sont consignées.
