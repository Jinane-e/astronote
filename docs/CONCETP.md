# Vision du projet

> Document de référence du concept global. Il couvre la vision à long terme,
> et pas uniquement le périmètre de la bêta.

## 1. Résumé

Créer une application personnalisable et multiplateforme — mobile, bureau et Web —
qui sert de compagnon pour organiser différents aspects de la vie personnelle,
professionnelle et collective.

L’application réunit, dans une structure cohérente, des outils de planification,
d’organisation, de suivi, de partage et de gestion. L’utilisateur choisit les
espaces, les contenus, les outils et l’affichage qui lui sont utiles, sans être
submergé par des informations sans rapport.

Le nom « AstroNote » est provisoire et reste à repenser.

## 2. Principes directeurs

- **Organisation maîtrisée :** isoler les sujets et éviter le bruit informationnel.
- **Personnalisation progressive :** proposer une expérience simple au départ,
  puis davantage d’options lorsque cela devient utile.
- **Modularité :** pouvoir ajouter, retirer, déplacer et faire évoluer les outils.
- **Vue locale et transversale :** consulter un sujet dans son contexte ou
  agréger des informations provenant de plusieurs sphères.
- **Partage contrôlé :** permettre la collaboration sans exposer les contenus
  non concernés.
- **Sécurité et confidentialité :** traiter les données personnelles avec
  prudence, appliquer le moindre privilège et documenter les choix de sécurité.
- **Maintenabilité :** privilégier une architecture testable, documentée et
  extensible.
- **Ouverture :** privilégier les outils, standards et intégrations open source
  lorsque cela convient au besoin.

## 3. Modèle d’organisation retenu pour la bêta

### Espace

Niveau supérieur, destiné à séparer de grands contextes de vie ou d’activité.

Exemples : Personnel, Professionnel, Association.

### Sphère

Niveau organisé à l’intérieur d’un Espace. Une Sphère regroupe un sujet, un
projet ou un domaine.

Exemples : Carrière, Jeux vidéo, Recherche d’appartement, Vacances été 2026,
Couture, Gestion globale.

### Capsule

Unité fonctionnelle que l’on ajoute à une Sphère. Le terme **Capsule** est
retenu pour la bêta à la place de « brique ».

Exemples : Capsule Agenda, Capsule Todo, Capsule Référentiel.

Une Capsule peut éventuellement être visible à plusieurs niveaux : par exemple,
une Capsule Agenda dans une Sphère et une vue agrégée de plusieurs agendas au
niveau de l’Espace. Les règles exactes de partage ou de synchronisation de ces
données restent à définir avant leur implémentation.

## 4. Expérience visée

- Chaque Espace, Sphère et Capsule doit pouvoir être consulté dans son contexte.
- L’utilisateur doit pouvoir accéder à une vue d’ensemble sans mélanger
  involontairement les données.
- Les pages d’accueil ou portails pourront proposer des widgets et des raccourcis.
- Les préférences visuelles et l’organisation de l’interface pourront évoluer
  progressivement.
- Un mode **Focus** est conservé dans la vision du produit : il aide à se
  concentrer sur un espace, un sujet ou une sélection de tâches, en limitant les
  distractions. Son fonctionnement précis reste à concevoir.

## 5. Domaines fonctionnels envisagés à long terme

La vision peut inclure, au fil du temps :

- tâches et projets : listes, tableaux Kanban, suivi;
- calendriers et planification;
- listes orientées, dont une **WishList**;
- référentiel de sites et d’outils en ligne, avec tags, favoris, usage fréquent
  et statut « à tester »;
- gestion et partage de contenus;
- galerie;
- gestion de comptes et coffre-fort;
- budgétisation et suivi financier;
- notes ou contenus structurés, si leur périmètre est clairement défini;
- widgets, tableaux de bord et agrégations entre Sphères;
- extensions et intégrations tierces, de préférence open source.

Cette liste est une vision, pas une promesse que chaque fonctionnalité sera
présente dans la bêta.

## 6. Modules, extensions et intégrations

À long terme, l’architecture devra permettre l’ajout de nouvelles Capsules sans
imposer de réécrire l’application entière. Les limites d’extension — données,
permissions, interfaces et intégrations — devront être conçues et documentées
avant d’ouvrir l’écosystème à des extensions tierces.

Une intégration externe devra être évaluée selon sa sécurité, sa maintenabilité,
son coût, ses conditions d’utilisation et la quantité de données qu’elle reçoit.

## 7. Partage et permissions

Le produit devra pouvoir prendre en charge des espaces partagés avec des droits
adaptés aux personnes concernées. Les permissions devront être explicites,
compréhensibles et limitées au besoin.

Les rôles, l’héritage des droits entre niveaux, les invitations, la révocation
d’accès et la visibilité des contenus sont à spécifier avant le développement
du partage collaboratif.

## 8. Sécurité, confidentialité et qualité

Exigences transversales :

- minimisation des données collectées;
- contrôle d’accès et séparation des données entre Espaces;
- gestion sûre des secrets et des identifiants;
- validation des données et protection des API;
- sauvegarde, export et suppression des données à définir;
- tests automatisés, revue des dépendances et journalisation prudente;
- documentation des menaces et des décisions d’architecture;
- ne jamais considérer un masquage visuel comme une mesure de sécurité.

Le traitement des mots de passe, informations financières et autres données
sensibles nécessitera une analyse de sécurité dédiée avant leur mise en bêta.

## 9. Public et stade de lancement

Le premier usage visé est personnel ou limité à un petit groupe : amis,
collaborateurs et testeurs. Cela permet de valider l’utilité, l’organisation
générale et l’ergonomie avant une éventuelle ouverture plus large.

## 10. Identité et vocabulaire

- Nom de travail : **AstroNote** — provisoire.
- Vocabulaire bêta : **Espace → Sphère → Capsule**.
- « Capsule » est le terme retenu pour la bêta; il pourra être réévalué après
  des tests utilisateurs.
- Identité visuelle, ton éditorial et nom final : à définir.
