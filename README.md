# Project proposition guide

<details>
  <summary>FR</summary>

## Introduction
Ce guide vous aidera à structurer votre proposition de projet MLOps en mettant l'accent sur les aspects MLOps plutôt que sur les détails de Data Science. L'objectif est de présenter un projet qui puisse être évalué pour son intégration dans le catalogue de projets de formation.

## Qu'est-ce que MLOps ?
MLOps (Machine Learning Operations) est une approche qui vise à standardiser et simplifier le développement, le déploiement et la maintenance des systèmes de machine learning.

Pour rappel, quelques points importants du MLOPS :
1. Gestion du code et des modèles
   * Outils de versioning (e.g., Git, DVC)
   * Stratégie de branching et de collaboration
2. Automatisation et CI/CD
   * Pipeline d'intégration continue
   * Tests automatisés (données, modèle, intégration)
   * Déploiement continu
3. Containerisation et orchestration
   * Utilisation de Docker pour l'encapsulation des modèles
   * Orchestration avec Kubernetes ou alternative
4. Monitoring et logging
   * Outils pour le suivi des performances du modèle
   * Système d'alerte pour la détection de drift
   * Centralisation des logs
5. Reproductibilité
   * Gestion des dépendances (e.g., conda, poetry)
   * Versioning des données d'entraînement
6. Gouvernance et sécurité
   * Gestion des accès et des secrets
   * Traçabilité des décisions du modèle
   * Conformité aux réglementations (si applicable)

## Structure de la proposition

### 1. Titre du projet
Choisissez un titre qui met en avant l'aspect MLOps de votre projet.

### 2. Résumé (150-200 mots)
Présentez brièvement :
* Le contexte du projet (type de modèle ML déjà développé)
* Les défis MLOps que le projet vise à résoudre
* Les principaux objectifs MLOps du projet
* L'impact attendu sur le processus de développement et de déploiement ML

### 3. Contexte et problématique MLOps
* Décrivez brièvement le modèle ML existant (sans entrer dans les détails techniques de Data Science)
* Identifiez les défis actuels dans le cycle de vie du modèle ML :
   * Reproductibilité
   * Mise à jour et versioning
   * Déploiement
   * Monitoring
   * Collaboration entre équipes
* Expliquez pourquoi une approche MLOps est nécessaire pour ce projet spécifique

### 4. Objectifs du projet MLOps
Listez 3-5 objectifs spécifiques, mesurables et pertinents pour MLOps.
Exemples :
* Réduire le temps de déploiement des modèles de X à Y jours
* Automatiser X% du pipeline de test et de déploiement
* Mettre en place un système de détection de drift avec un temps de réponse de X heures

### 5. Architecture technique MLOps
* Présentez un schéma détaillé de l'architecture MLOps proposée présentant les composants clés (si vous en avez)

### 6. POC GitHub, sources de données et ressources utiles
* Fournissez un lien vers un POC GitHub de votre projet
* Listez les sources de données que vous comptez utiliser (assurez-vous qu'elles sont libres et open source)
* Indiquez toute ressource utile pour la compréhension ou la mise en œuvre de votre projet (articles, tutoriels, documentation)

### 7. Évaluation des risques et stratégies de mitigation
Identifiez les risques spécifiques au projet MLOps et proposez des stratégies d'atténuation.
Exemple :
* Risque : Résistance au changement de la part des équipes
* Mitigation : Plan de formation et démonstration des bénéfices à court terme

### 8. Métriques de succès
Définissez des KPIs spécifiques à MLOps :
* Temps de déploiement des modèles
* Fréquence des mises à jour réussies
* Temps moyen de détection et de résolution des problèmes
* Taux d'automatisation du pipeline

### 9. Potentiel d'intégration dans le catalogue de projets
Expliquez pourquoi ce projet serait un bon ajout au catalogue :
* Compétences MLOps couvertes
* Applicabilité à d'autres contextes ou industries
* Potentiel d'évolution et d'extension du projet

### 10. Conclusion
Résumez les points clés de votre proposition et réaffirmez l'importance de l'approche MLOps pour ce projet.

## Conseils pour l'évaluation
* Mettez l'accent sur l'aspect pratique et applicable du projet MLOps
* Démontrez une compréhension approfondie des principes et outils MLOps
* Montrez comment le projet aborde les défis courants en production de modèles ML
* Soulignez le potentiel pédagogique du projet pour d'autres apprenants

Ce guide vous aidera à créer une proposition solide axée sur MLOps, adaptée pour l'évaluation et l'intégration potentielle dans un catalogue de projets de formation.
</details>

<details>
  <summary>EN</summary>

## Introduction
This guide will help you structure your MLOps project proposal by focusing on MLOps aspects rather than Data Science details. The objective is to present a project that can be evaluated for inclusion in the training projects catalog.

## What is MLOps?
MLOps (Machine Learning Operations) is an approach that aims to standardize and simplify the development, deployment, and maintenance of machine learning systems.

As a reminder, here are some important MLOps points:
1. Code and model management
   * Versioning tools (e.g., Git, DVC)
   * Branching and collaboration strategy
2. Automation and CI/CD
   * Continuous integration pipeline
   * Automated testing (data, model, integration)
   * Continuous deployment
3. Containerization and orchestration
   * Use of Docker for model encapsulation
   * Orchestration with Kubernetes or alternatives
4. Monitoring and logging
   * Tools for tracking model performance
   * Alert system for drift detection
   * Log centralization
5. Reproducibility
   * Dependency management (e.g., conda, poetry)
   * Versioning of training data
6. Governance and security
   * Access and secrets management
   * Traceability of model decisions
   * Compliance with regulations (if applicable)

## Proposal Structure

### 1. Project Title
Choose a title that highlights the MLOps aspect of your project.

### 2. Summary (150-200 words)
Briefly present:
* The project context (type of ML model already developed)
* The MLOps challenges the project aims to solve
* The main MLOps objectives of the project
* The expected impact on the ML development and deployment process

### 3. MLOps Context and Challenge
* Briefly describe the existing ML model (without delving into Data Science technical details)
* Identify the current challenges in the ML model lifecycle:
   * Reproducibility
   * Updating and versioning
   * Deployment
   * Monitoring
   * Team collaboration
* Explain why an MLOps approach is necessary for this specific project

### 4. MLOps Project Objectives
List 3-5 specific, measurable, and relevant MLOps objectives.
Examples:
* Reduce model deployment time from X to Y days
* Automate X% of the testing and deployment pipeline
* Implement a drift detection system with a response time of X hours

### 5. MLOps Technical Architecture
* Present a detailed diagram of the proposed MLOps architecture showcasing the key components (if available)

### 6. GitHub POC, Data Sources, and Useful Resources
* Provide a link to a GitHub POC of your project
* List the data sources you plan to use (ensure they are free and open source)
* Mention any useful resources for understanding or implementing your project (articles, tutorials, documentation)

### 7. Risk Assessment and Mitigation Strategies
Identify the specific risks related to the MLOps project and propose mitigation strategies.
Example:
* Risk: Resistance to change from teams
* Mitigation: Training plan and demonstration of short-term benefits

### 8. Success Metrics
Define specific MLOps KPIs:
* Model deployment time
* Frequency of successful updates
* Average time for problem detection and resolution
* Automation rate of the pipeline

### 9. Potential for Integration into the Projects Catalog
Explain why this project would be a good addition to the catalog:
* Covered MLOps skills
* Applicability to other contexts or industries
* Potential for project evolution and expansion

### 10. Conclusion
Summarize the key points of your proposal and reaffirm the importance of the MLOps approach for this project.

## Evaluation Tips
* Emphasize the practical and applicable aspects of the MLOps project
* Demonstrate a thorough understanding of MLOps principles and tools
* Show how the project addresses common challenges in ML model production
* Highlight the educational potential of the project for other learners

This guide will help you create a solid proposal focused on MLOps, suitable for evaluation and potential inclusion in a training projects catalog.

</details>
