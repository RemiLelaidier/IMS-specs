Internship Management System (IMS)
===

## Contents

1. [Introduction](#introduction)
2. [Changements Nécessaires](#changements-nécessaires)
3. [Exigences Métiers](#exigences-métiers)
4. [Changements Techniques](#changements-techniques)
5. [Dépendances de déploiement](#dépendances-de-déploiement)
6. [Mise à niveau de la stratégie de données](#mise-à-niveau-de-la-stratégie-de-données)
7. [Tests Requis](#tests-requis)
8. [Questions en suspens](#questions-en-suspens)
9. [Ressources Extérieures](#ressources-extérieures)

---

Introduction
---

L'objectif de ce document est de fournir un système de gestion des stages pour Unice afin de simplifier le processus actuel.

Changements Nécessaires
---

Le besoin principal vient du sytème actuel de gestion des stages. Le processus actuel peut générer des problèmes.


Exigences Métiers
---

**P1** Analyse du sytème des getion actuel

**P2** Début du travail sur le système de gestion IMS (Internship Management System)

Changements Techniques
---

### Le processus actuel est :

- Validation du stage par un professeur ou une autre personne
- Après la validation, l'étudiant récupére sa convention
- La convention est remplie par l'étudiant et son entreprise (3 fois)
- L'administration peut affecter un tuteur académique
- Les infos sont à nouveau saisies pour garder une traçabilité
- L'administration envoie la convention remplie à la scolarité
- La convention revient et est rendue à l'étudiant

### L'objectif est :

- L'étudiant se connecte sur l'application web IMS et fournit ses informations
- L'administration peut suivre toutes les informations sur un panel d'administration, valider la convention / envoyer des mails d'erreurs
- Quand la convention est prête, elle est imprimée et envoyée à la scolarité
- Quand la convention revient, les changements sont entrés dans le sytème.
- Des emails sont envoyés à l'étudiant et son tuteur quand il y a des changements, pour que tout soit à jour (à définir)


Dépendances de déploiement
---

Nou devons fournir de la documentation et des formations pour éviter les problèmes.


Mise à niveau de la stratégie de données
---

Rien à garder ou demander les données actuelles


Tests Requis
---

Développement en TDD - Tout doit être testé avant d'être envoyé sur la branche Master
Vérification avec les étudiants
Vérification avec l'administration


Questions en suspens
---

- Quoi utiliser ? Technologiquement ?
- Interface Utilisateur à définir - Etudiants & Administration


Ressources Extérieures
---

- Outil actuel (vieux mais fonctionnel) : http://conv.polytech.unice.fr/conv/


Revisions
===
* **09/10/17** : Specs initiales par Léonard
* **18/10/17** : Traduction par Rémi
 