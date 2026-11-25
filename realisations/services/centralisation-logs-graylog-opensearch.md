# Centralisation des journaux avec Graylog et OpenSearch

## 1. Identification générale

- **Auteur** — Timothy Valentin, BTS SIO option SISR.
- **Cadre** — TP de formation — lycée Henri Matisse.
- **Période** — Formation BTS SIO SISR.

## 2. Contexte et objectifs

Collecter les journaux de plusieurs machines Linux et les rendre consultables depuis une interface commune.

## 3. Démarche et environnement technique

**Outils** — Proxmox VE, Ubuntu Server, Docker Compose, Graylog, OpenSearch, MongoDB, Rsyslog.

J’ai déployé la pile de collecte dans des conteneurs et configuré l’envoi des journaux depuis les machines Linux. J’ai vérifié leur arrivée, créé un accès en lecture seule et réglé la rotation des index. J’ai diagnostiqué un échec de démarrage de MongoDB lié à la compatibilité du processeur.

## 4. Rôle et contribution personnelle

J’ai installé la pile, configuré la collecte et les accès, puis vérifié les résultats et diagnostiqué l’échec de démarrage.

## 5. Livrables et preuves associées

- [Fiche détaillée sur mon portfolio](https://timothy-valentin.github.io/realisations/centralisation-logs-graylog-opensearch/)
- [Schéma de collecte et de stockage des journaux](./preuves/graylog-centralisation.svg) — schéma de principe.
- [Validation de la collecte](https://timothy-valentin.github.io/realisations/centralisation-logs-graylog-opensearch/#3-validation).
- [Vérification du compte en lecture seule](https://timothy-valentin.github.io/realisations/centralisation-logs-graylog-opensearch/#sécurité-des-accès--un-compte-en-lecture-seule).

## 6. Compétences du bloc 1 mobilisées

- **B1.1** — Mettre en place un accès en lecture seule et en vérifier le périmètre.
- **B1.2** — Identifier la cause d’un incident de démarrage.
- **B1.5** — Déployer et vérifier un service de collecte et de consultation.

## 7. Bilan réflexif et auto-évaluation

Les événements sont regroupés dans un flux, enrichis et consultables avec un compte dédié. Pour un déploiement en production, je retiens le besoin de versions maintenues et d’un transport chiffré.
