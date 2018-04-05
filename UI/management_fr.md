# UI IMS

## Management

Le but principal de ce document est de définir l'interface utilisateur pour les chargés de stages (CDS).

Le CDS doit pouvoir suivre la progression des étudiants, leur envoyer des rappels ou des documents.

## Page Home

La page Home doit afficher toutes les informations que le CDS doit connaître.
Ces informations seront affichées dans plusieurs composants composants la page Home.

### Composant "Students Status"

Ce composant doit afficher la liste des étudiants et leur statut.
Le composant posséde plusieurs tabs (1 par promotion) permettant la liste des étudiants dans chaque promotion.
Chaque étudiant est un élèment qui affiche les informations relatives à l'étudiant :
- Le nom
- Le prénom
- Le numéro étudiant
- Un code couleur.

Le code couleur définit le statut de chaque étudiant :
- Vert : L'étudiant a une convention de stage signée et complète, il est prêt à aller en stage.
- Orange : L'étudiant a une convention où il manque des signatures et/ou des infos.
- Rouge : Aucune trace de la convention de l'étudiant.
- Gris : L'étudiant ne s'est pas encore inscrit sur l'application

Si le CDS clique sur un item, cela le méne sur la page de l'étudiant.

### Composant "Events"

Ce composant permet d'afficher les derniers événements (ex: Gérard Dupont a déposé sa convention de stage).

------TODO

## Page Etudiant

La page étudiant permet d'afficher les données relatives à un étudiant et les différents événements de cet étudiant (date de signature de l'entreprise, date de dépôt de la convention).

Pour se faire, la page est composé de plusieurs composants.

### Composant "Student Info"

Ce composant affiche les infos de l'étudiant dans plusieurs sections.

Section Generale:
- Nom & Prénom
- Date & Lieu de naissance
- Adresse
- Nationalité
- (Lien vers responsabilité civile)?
- Portable
- Fixe

Section Scolaire:
- Numéro étudiant
- Promotion

Section Stage:
- Sujet du stage
- Description du stage
- Date début & Fin
- Rémunération
- Horaires
- Nom de l'entreprise
- Adresse de l'entreprise
- Téléphone entreprise
- SIRET
- Nom & prénom du tuteur en entreprise
- Portable du tuteur en entreprise
- Nom & prénom du tuteur académique
- Portable du tuteur académique
- Notes de l'étudiant

Section Statut:
- Cette section reprend le système de code couleur définit plus haut dans ce document (Page Home).

### Composant "Student Events"

------ TODO

Revisions
===
* **05/04/18** : Première version après réunion avec Mr. Winter