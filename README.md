# 🏠 Projet 2 - Base de Données SQL Immobilier

**Résumé du projet :**
Conception d'une base de données relationnelle SQL pour analyser le marché immobilier français (données DVF 2020). L'objectif était de structurer les données publiques de la DGFiP en schéma normalisé 3NF, puis de répondre à 12 analyses stratégiques via requêtes SQL complexes (ventes par région, TOP départements prix/m², évolutions trimestrielles, segmentations par typologie de biens).

**Tâches réalisées :**
**Modélisation de la base de données** : Création du schéma relationnel normalisé (tables Mutations, Biens, Communes, Régions), dictionnaire de données exhaustif (43 attributs documentés).
**Nettoyage et import des données** : Traitement CSV avec Power Query (valeurs manquantes, doublons, types incompatibles), import dans SQLite avec respect des contraintes d'intégrité.
**Développement de 12 requêtes SQL avancées** : Agrégations (GROUP BY, HAVING), jointures multiples, CTEs (Common Table Expressions), fonctions fenêtres (ROW_NUMBER, PARTITION BY), calculs de taux d'évolution et ratios.
**Présentation des résultats** : Support PowerPoint avec méthodologie de modélisation, justification des choix techniques, et résultats clés des analyses (disparités régionales, impact COVID, segmentations).
**Compétences et outils mobilisés** :
**Outils** : SQLite (SGBD), Power Query / Excel (nettoyage), SQL (requêtes analytiques).
**Expertise** : Modélisation relationnelle (3NF), SQL avancé (jointures, CTEs, agrégations), data cleaning, documentation technique.
**Livrables** :
Schéma relationnel et dictionnaire de données
Base SQLite (.db) peuplée S1 2020
Script SQL avec 12 requêtes commentées
Support de présentation méthodologie + résultats
