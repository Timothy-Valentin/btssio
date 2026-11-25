# Mise en place d’un réseau d’entreprise virtualisé

## 1. Identification générale

- **Auteur** — Timothy Valentin, BTS SIO option SISR.
- **Cadre** — TP de formation — lycée Henri Matisse.
- **Période** — Formation BTS SIO SISR.

## 2. Contexte et objectifs

Construire une infrastructure de formation avec annuaire, adressage automatique, filtrage et sauvegardes.

## 3. Démarche et environnement technique

**Outils** — Proxmox VE, pfSense, Windows Server (AD DS, DNS, DHCP, GPO), clients Windows et Ubuntu.

J’ai créé les VM, configuré pfSense et installé les services du domaine. J’ai joint les postes Windows au domaine et vérifié l’adressage, la résolution DNS et l’accès réseau depuis les clients. J’ai contrôlé l’application des GPO sur Windows, puis copié les sauvegardes des VM sur mon ordinateur personnel.

## 4. Rôle et contribution personnelle

J’ai installé et configuré l’infrastructure, vérifié les services et réalisé les sauvegardes.

## 5. Livrables et preuves associées

- [Fiche détaillée sur mon portfolio](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/)
- [Schéma Proxmox, pfSense, Active Directory, DNS et DHCP](./preuves/reseau-complet.svg) — schéma de principe.
- [Procédure de sauvegarde et copie hors serveur](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/#7-les-sauvegardes).
- [Vérifications du domaine et des services](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/#vérifications).

## 6. Compétences du bloc 1 mobilisées

- **B1.1** — Gérer les comptes et groupes ainsi que les sauvegardes du parc virtualisé.
- **B1.5** — Déployer et vérifier les services AD DS, DNS et DHCP.

## 7. Bilan réflexif et auto-évaluation

Les clients obtiennent leur configuration réseau et les GPO s’appliquent sur Windows. La copie hors serveur est en place. Le test de restauration reste à effectuer.
