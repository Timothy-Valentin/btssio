# Étude des besoins réseau et validation sur maquette pour un bâtiment judiciaire

## 1. Identification générale

- **Auteur** — Timothy Valentin, BTS SIO option SISR.
- **Cadre** — Stage de première année, du 25 mai au 28 juin 2026.
- **Organisation d’accueil** — DIT du ministère de la Justice, Toulouse (Jolimont).
- **Modalité** — Travail réalisé sous l’encadrement de mon tuteur, avec des échanges auprès des services concernés et de l’équipe informatique.

## 2. Contexte et objectifs

La DIT préparait l’infrastructure réseau d’un nouveau bâtiment judiciaire. Ma mission consistait à recenser les besoins des services, à les traduire en une proposition d’infrastructure et à présenter mes choix. Le volet pratique consistait à diagnostiquer des pannes sur une maquette physique et à vérifier le rétablissement des communications après correction.

## 3. Démarche et environnement technique

1. J’ai mené des entretiens, reformulé les demandes et organisé la synthèse par service. J’ai fait valider cette synthèse par l’équipe de la DIT.
2. J’ai proposé de séparer les populations et les flux selon leur sensibilité, puis j’ai présenté et défendu la proposition devant un jury de spécialistes.
3. J’ai travaillé sur une maquette de commutateurs, routeurs et pare-feu reliée à un réseau distant. J’ai utilisé une liaison console avec PuTTY et une syntaxe de type Cisco IOS.
4. Pour les pannes introduites par mon tuteur, j’ai vérifié le câblage et les interfaces, puis la commutation, le routage et le filtrage. Après correction, j’ai refait un test de bout en bout.

## 4. Rôle et contribution personnelle

J’ai assuré les entretiens, la synthèse des besoins et la préparation de la proposition. J’ai présenté les choix techniques et répondu aux questions du jury. Sur la maquette, j’ai localisé les pannes, appliqué les corrections et vérifié le résultat sous l’encadrement de mon tuteur.

## 5. Livrables et preuves associées

- [Schéma de principe de la maquette physique](./preuves/justice-maquette.svg).
- [Compte rendu de validation et sources de stage](./preuves/compte-rendu-validation.md), avec les liens vers le rapport PDF et les résultats publiés.

## 6. Compétences du bloc 1 mobilisées

- [x] **B1.2 — Répondre aux incidents et demandes d’assistance.** Diagnostiquer et corriger des pannes réseau sur la maquette du stage.
- [x] **B1.4 — Travailler en mode projet.** Recueillir les besoins, les faire valider et défendre une proposition d’infrastructure.
- [x] **B1.5 — Mettre à disposition des utilisateurs un service informatique.** Tester les communications de bout en bout après intervention sur la maquette.

## 7. Bilan réflexif et auto-évaluation

J’ai appris à passer de besoins exprimés par les services à des choix d’infrastructure justifiés. Sur la maquette, j’ai appris à isoler une panne en vérifiant chaque couche et à contrôler la communication après une correction. Pour une prochaine intervention, je noterais pour chaque test le symptôme initial, le résultat attendu et le résultat obtenu, afin de faciliter la reprise du diagnostic.
