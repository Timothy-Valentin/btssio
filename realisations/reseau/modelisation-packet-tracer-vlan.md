# Segmentation VLAN, routage inter-VLAN et DHCP sur Packet Tracer

## 1. Identification générale

- **Auteur** — Timothy Valentin, BTS SIO option SISR.
- **Cadre** — TP de formation — lycée Henri Matisse.
- **Période** — Formation BTS SIO SISR.

## 2. Contexte et objectifs

Séparer deux services en VLAN, permettre les échanges nécessaires et distribuer automatiquement les adresses.

## 3. Démarche et environnement technique

**Outils** — Cisco Packet Tracer, VLAN 802.1Q, routage inter-VLAN, DHCP.

J’ai créé les VLAN et affecté les ports, puis configuré le trunk et une sous-interface de routeur par VLAN. J’ai paramétré les étendues DHCP et étudié le relais DHCP pour le cas où le serveur est dans un autre réseau. J’ai vérifié l’adressage attribué et les échanges dans et entre les VLAN.

## 4. Rôle et contribution personnelle

J’ai conçu, configuré et vérifié la maquette dans le simulateur.

## 5. Livrables et preuves associées

- [Fiche détaillée sur mon portfolio](https://timothy-valentin.github.io/realisations/modelisation-packet-tracer-vlan/)
- [Schéma des VLAN, du trunk et du routage](./preuves/packet-tracer-vlan.svg) — schéma de principe.
- [Configuration et contrôles de la maquette](https://timothy-valentin.github.io/realisations/modelisation-packet-tracer-vlan/#réalisation).

## 6. Compétences du bloc 1 mobilisées

- **B1.5** — Mettre en place et vérifier des services réseau sur une maquette.

## 7. Bilan réflexif et auto-évaluation

La maquette simule un réseau segmenté avec distribution automatique des adresses. Le mode simulation permet de suivre le trajet des trames et de vérifier les hypothèses de configuration.
