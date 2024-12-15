# Tâches Initiales - Task3.md

## Objectif
Documenter l'implémentation des fonctionnalités liées à la gestion des tâches, des projets, et la mise en place de l'environnement Docker pour le backend, tout en mettant en place une suite de tests pour le backend et le frontend.

---

### Tâche 1 : Implémentation des fonctionnalités de gestion des tâches
- **Description** : Développer les fonctionnalités de gestion des tâches, incluant la modification, la suppression et l'affichage d'un code couleur en fonction de l'état des tâches.
- **Statut** : Terminé
- **Détails** : 
  - **Modifier des tâches** : Permettre aux utilisateurs de modifier les tâches existantes en fonction de leur statut et priorités.
  - **Supprimer des tâches** : Ajouter la possibilité pour les utilisateurs de supprimer des tâches.
  - **Affichage d'un code couleur pour spécifier l'état d'une tâche** : Implémentation d'un système de couleurs pour indiquer l'état de la tâche (par exemple, vert pour terminé, rouge pour en retard).

---

### Tâche 2 : Implémentation des fonctionnalités liées aux projets
- **Description** : Développer les fonctionnalités permettant la gestion des projets, comme la suppression de projets et l'ajout de collaborateurs par l'administrateur.
- **Statut** : Terminé
- **Détails** : 
  - **Supprimer des projets** : Implémentation de la possibilité pour les utilisateurs administrateurs de supprimer un projet.
  - **Ajouter des collaborateurs au projet** : Permettre à un administrateur de projet d'ajouter de nouveaux collaborateurs.

---

### Tâche 3 : Configuration du Docker
- **Description** : Configurer Docker pour le backend, en créant des fichiers nécessaires pour la gestion des conteneurs et la communication entre eux.
- **Statut** : Terminé
- **Détails** :
  - **Dockerfile pour le backend** : Création d'un Dockerfile pour configurer l'environnement de développement du backend.
  - **Fichier docker-compose.yml** : Configuration d'un fichier `docker-compose.yml` pour gérer plusieurs services Docker.
  - **Réseaux Docker** : Mise en place de réseaux Docker pour permettre la communication entre les conteneurs.
  - **Pipeline CI Github** : Configuration des containers Docker pour être utilisés dans une pipeline CI Github pour l'intégration continue.

---

### Tâche 4 : Implémentation des tests
- **Description** : Développer des tests unitaires pour valider le bon fonctionnement du backend et du frontend, et configurer la pipeline CI pour l'automatisation des tests.
- **Statut** : Terminé
- **Détails** :
  - **Tests backend** : Écriture de tests unitaires pour les fonctionnalités liées aux tâches, aux sprints et aux projets.
  - **Tests frontend** : Rédaction de tests unitaires pour les composants frontend.
  - **Automatisation des tests via la pipeline CI** : Mise en place d'une pipeline CI pour exécuter les tests automatiquement lors des commits.

---

### Tâche 5 : Mise au propre du code
- **Description** : Assurer la qualité et la lisibilité du code en documentant et en refactorisant les parties pertinentes du projet.
- **Statut** : Terminé
- **Détails** : 
  - **Documentation backend** : Documentation complète des fonctionnalités du backend, des routes, des modèles et des contrôleurs.
  - **Documentation frontend** : Rédaction d'une documentation pour le frontend, expliquant la structure des composants et des services.
  - **Refactoring du code** : Refactorisation pour améliorer la lisibilité, la maintenabilité et les performances du code.

---

### Tâche 6 : Implémentation de la section test
- **Description** : Implémenter la section des tests, si cela n’a pas été réalisé précédemment.
- **Statut** : Non réalisé
- **Détails** : Cette tâche consiste à créer une interface utilisateur pour visualiser les résultats des tests automatisés dans l’application.

---
