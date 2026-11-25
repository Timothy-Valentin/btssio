# Préparation de l’épreuve E5

Timothy Valentin — BTS SIO option SISR, session 2027

[Portfolio public](https://timothy-valentin.github.io/) · [Fiches et preuves](./realisations/README.md) · [Suivi des savoirs](./competences_acquises.md)

## Compétences du bloc 1 et points à documenter

| Compétence | Exemple à présenter | Preuve ou complément à préparer |
| --- | --- | --- |
| B1.1 — Gérer le patrimoine informatique | [Inventaire GLPI](./realisations/gestion_de_parc/installation-glpi-ubuntu.md) et [sauvegarde des VM](./realisations/reseau/reseau-entreprise-proxmox-ad-pfsense.md). | Exporter un inventaire anonymisé. Restaurer une VM en environnement isolé et consigner le résultat. |
| B1.2 — Répondre aux incidents et aux demandes | [Simulation de support GLPI](./realisations/gestion_de_parc/installation-glpi-ubuntu.md) et [diagnostic réseau en stage](./realisations/stage_justice/fiche_stage_justice.md). | Conserver un ticket anonymisé montrant le diagnostic, l’intervention et le résultat. |
| B1.3 — Développer la présence en ligne de l’organisation | Le [portfolio personnel](./realisations/developpement_professionnel/portfolio-github-pages.md) documente la création et la publication d’un site. | Documenter une réalisation pour une organisation, avec son besoin, la contribution apportée et, selon le cas, une mesure de visibilité. |
| B1.4 — Travailler en mode projet | [Recueil des besoins et proposition d’infrastructure en stage](./realisations/stage_justice/fiche_stage_justice.md). | Joindre un planning ou un suivi de tâches anonymisé et expliquer un écart s’il a été mesuré. |
| B1.5 — Mettre à disposition un service | [Collecte de journaux et vérification de la consultation dans Graylog](./realisations/services/centralisation-logs-graylog-opensearch.md). | Consigner les critères, les résultats attendus et observés, ainsi que les conditions d’acceptation. |
| B1.6 — Organiser son développement professionnel | [Portfolio](./realisations/developpement_professionnel/portfolio-github-pages.md), [entraînement réseau](./realisations/developpement_professionnel/root-me-analyse-protocoles-en-clair.md) et [veille sur les passkeys](https://timothy-valentin.github.io/veille/methodologie-outils-veille/). | Préparer un exemple de décision technique éclairée par la veille. |

Les savoirs S3, S5, S10, S11, S13, S14, S15 et S17 restent à documenter dans le [tableau de suivi](./competences_acquises.md). Les priorités sont le test de restauration (S3 et S4), le suivi du projet (S14 et S15) et une recette formalisée (S17). Le tableau E5 reprend les six compétences du bloc 1. Les savoirs S1 à S18 restent dans le suivi pédagogique du dépôt.

## Projet professionnel après le BTS

Mon objectif est de poursuivre mes études en cybersécurité et de trouver une alternance pour la rentrée 2027. Les pistes que j’explore sont le travail en SOC et l’administration sécurisée des systèmes et réseaux. La centralisation des journaux avec Graylog me donne un exemple concret de supervision. Mon projet de réseau virtualisé et ma veille sur les passkeys me permettent d’approfondir la gestion des accès et l’authentification. D’ici la rentrée, je veux savoir présenter un test de restauration et des résultats de recette reproductibles. [Parcours](https://timothy-valentin.github.io/parcours/) · [Veille](https://timothy-valentin.github.io/veille/)

## Trame de présentation en 10 minutes

| Temps | À présenter à l’oral | Support |
| --- | --- | --- |
| 0:00–1:00 | Mon parcours, mon choix de l’option SISR et l’organisation du portfolio. | [Parcours](https://timothy-valentin.github.io/parcours/) |
| 1:00–3:30 | Stage de première année. Expliquer le besoin du bâtiment, mon rôle, la proposition, puis un diagnostic par couches sur la maquette. | [Fiche et preuves du stage](./realisations/stage_justice/fiche_stage_justice.md#5-livrables-et-preuves-associées) |
| 3:30–5:30 | GLPI. Montrer le trajet d’un ticket, expliquer la différence entre urgence et impact et rappeler le résultat de la simulation. | [Fiche et schéma GLPI](./realisations/gestion_de_parc/installation-glpi-ubuntu.md#5-livrables-et-preuves-associées) |
| 5:30–7:30 | Graylog. Suivre un événement du poste source à l’interface et expliquer la vérification de la collecte et de l’accès en lecture seule. | [Fiche et schéma Graylog](./realisations/services/centralisation-logs-graylog-opensearch.md#5-livrables-et-preuves-associées) |
| 7:30–9:00 | Identité professionnelle, publication du portfolio et exemple de veille sur les passkeys. | [Portfolio](https://timothy-valentin.github.io/) · [Veille](https://timothy-valentin.github.io/veille/) |
| 9:00–10:00 | Progrès, test de restauration encore à réaliser et projet d’alternance en cybersécurité. | [Tableau de suivi](./competences_acquises.md) |

À la répétition, ouvrir les trois preuves principales à l’avance et relever le temps réel de chaque partie.

## Pièces à compléter avant le dépôt

- Renseigner le numéro de candidat et préciser les périodes des TP et des projets dont les dates exactes manquent dans le tableau de synthèse.
- Vérifier le modèle applicable à la session 2027 auprès de l’établissement. La version de travail s’appuie sur le [modèle 2026 publié sur Toutatice par le rectorat](https://www.toutatice.fr/portail/share/TBIRcZ?l=wNsQIf). Conserver le classeur sur un espace personnel, hors Git.
- Récupérer l’attestation signée du premier stage et les bilans hebdomadaires. Ajouter la deuxième période et ses pièces lorsqu’elles seront disponibles.
