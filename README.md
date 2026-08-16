# github-profile-CONTRIBUTING.md
Studio SDFB CREATIVE DEV LAB : github/profile/CONTRIBUTING.md

# Guide de Contribution - Studio SDFB Creative Dev Lab

Bienvenue dans le pôle de développement du protocole Dorian Codex pour l'IA (Horizon 2026-2030). Pour faire passer ce projet d'un manifeste conceptuel à un framework industriel, nous appliquons des standards de gouvernance stricts.

## 1. Stratégie de Gestion des Branches (Trunk-Based Development)
* **`main` (Branche Principale)** : Contient le code stable, audité et prêt pour la production. Aucun commit direct n'est autorisé sur `main`.
* **`feature/` ou `fix/` (Branches Éphémères)** : Toute modification ou ajout de fonctionnalité doit être développé sur une branche dédiée (ex: `feature/implémentation-h-safe`).
* **Fusion** : Le passage d'une branche à `main` se fait exclusivement via une *Pull Request* (PR) après validation des tests automatisés (CI).

## 2. Processus de Contribution et Traçabilité
1. **Ouvrir une Issue** : Avant de coder, documentez le problème ou l'évolution souhaitée en utilisant nos modèles de tickets.
2. **Créer une Pull Request** : Liez explicitement votre PR à l'Issue correspondante (`Closes #XYZ`).
3. **Qualité du Code** : Votre code doit passer l'intégralité de la suite de tests et respecter les standards de formatage avant d'être fusionné.

## 3. Code de Conduite
Nous exigeons un environnement collaboratif respectueux, inclusif et rigoureux. Les contributions purement spéculatives sans fondement technique ou mathématique exploitable seront rejetées par l'équipe de maintenance.
