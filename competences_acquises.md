# 📋 Tableau de Bord d'Acquisition des Savoirs (Bloc 1 — Épreuve E5)

**Étudiant :** Timothy Valentin — BTS SIO option SISR, 2e année — [portfolio](https://timothy-valentin.github.io)

Ce document assure la traçabilité de votre montée en compétences sur le **Bloc 1 : Support et mise à disposition de services informatiques** (Unité U4).

> **Consignes pour l'étudiant :**
> 1. À votre arrivée en BTS, tous les savoirs ci-dessous sont au format barré (`~~...~~`).
> 2. Lorsqu'un savoir a été mis en œuvre, compris et validé lors d'un TP, d'un projet en Atelier de Professionnalisation (AP) ou d'un stage :
>    * Retirez les tildes `~~` pour repasser le code et son intitulé en texte clair / gras.
>    * Cochez la case `[x]`.
>    * Renseignez le contexte ou collez le lien vers votre fiche de situation / commit Git.
> 3. Commitez régulièrement votre fichier (`git commit -m "docs: acquisition du savoir S4 suite TP PRA"`).

---

### Activité 1.1 : Gérer le patrimoine informatique

- [x] **S1 — Patrimoine informatique et système informatique :** définition, outils de gestion et de recensement des actifs (CMDB), composants matériels et logiciels.  
  *Preuve / Contexte de validation :* TP GLPI : installation du serveur et inventaire du parc (ordinateurs, logiciels, matériels réseau) — [fiche GLPI](https://timothy-valentin.github.io/realisations/installation-glpi-ubuntu/).

- [x] **S2 — Systèmes d'exploitation et gestion des habilitations :** gestion des comptes utilisateurs, droits d'accès, privilèges, groupes et politiques d'authentification.  
  *Preuve / Contexte de validation :* Comptes, groupes, unités d'organisation et GPO dans Active Directory — [fiche Réseau d'entreprise complet](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/) ; comptes utilisateurs et administrateur dans GLPI — [fiche GLPI](https://timothy-valentin.github.io/realisations/installation-glpi-ubuntu/) ; compte en lecture seule dans Graylog — [fiche Graylog](https://timothy-valentin.github.io/realisations/centralisation-logs-graylog-opensearch/).

- [ ] ~~**S3 — Disponibilité et continuité d'activité :** enjeux techniques, économiques et juridiques de la disponibilité ; plans de continuité (PCA) et plans de reprise d'activité (PRA).~~  
  *Preuve / Contexte de validation :* 

- [x] **S4 — Sauvegardes et restaurations :** typologies (totale, incrémentale, différentielle), supports physiques et logiques, stratégies de sauvegarde et protocoles de test de restauration.  
  *Preuve / Contexte de validation :* Sauvegarde des machines virtuelles depuis Proxmox VE, puis copie sur mon ordinateur personnel pour disposer d'un exemplaire hors du serveur — [fiche Réseau d'entreprise complet](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/). Test de restauration : à réaliser.

- [ ] ~~**S5 — Cadre juridique et contractuel du patrimoine :** typologie des licences logicielles, tarification, contrats de prestation, obligations légales d'archivage des données, valeur juridique de la charte informatique et responsabilité du salarié utilisateur.~~  
  *Preuve / Contexte de validation :* 

---

### Activité 1.2 : Répondre aux incidents et aux demandes d'assistance et d'évolution

- [x] **S6 — Gestion des incidents et assistance (Helpdesk) :** outils de ticketing, cycle de traitement des demandes, normes et référentiels (ITIL), bases de connaissances, procédures de télé-assistance.  
  *Preuve / Contexte de validation :* TP GLPI : tickets de gravités différentes créés par des utilisateurs depuis plusieurs postes, puis traités avec le compte administrateur — [fiche GLPI](https://timothy-valentin.github.io/realisations/installation-glpi-ubuntu/).

- [x] **S7 — Diagnostic et résolution :** méthodologie d'analyse causale de panne, recherche de causes racines, outils de diagnostic technique et de test dégressif.  
  *Preuve / Contexte de validation :* Stage : pannes injectées sur une maquette physique, diagnostic par couches du modèle OSI — [fiche Stage au Ministère de la Justice](https://timothy-valentin.github.io/realisations/deploiement-reseau-nouveau-batiment-justice/) ; résolution d'une panne de démarrage liée au processeur — [fiche Graylog](https://timothy-valentin.github.io/realisations/centralisation-logs-graylog-opensearch/).

- [x] **S8 — Fondamentaux des réseaux et des équipements :** modèles de référence (OSI, TCP/IP), médias d'interconnexion, protocoles de base, plan d'adressage IP, sous-réseaux, routage, services de nommage (DNS) et composants matériels clients/serveurs.  
  *Preuve / Contexte de validation :* VLAN, routage inter-VLAN, adressage et DHCP sur Packet Tracer — [fiche Packet Tracer](https://timothy-valentin.github.io/realisations/modelisation-packet-tracer-vlan/) ; DNS et DHCP du domaine — [fiche Réseau d'entreprise complet](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/).

- [x] **S9 — Systèmes et virtualisation :** fonctionnalités des systèmes d'exploitation clients et serveurs (Linux, Windows), rôles et principes fondamentaux de la virtualisation.  
  *Preuve / Contexte de validation :* Installation de Proxmox VE et création de machines virtuelles Debian, Ubuntu et Kali — [fiche Serveur Proxmox](https://timothy-valentin.github.io/realisations/serveurs-reconditionnes-proxmox/) ; clients Windows et Ubuntu, Windows Server — [fiche Réseau d'entreprise complet](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/).

- [ ] ~~**S10 — Développement et automatisation système :** algorithmique de base, structures de données, langages de commande et scripts d'administration/automatisation (Bash, PowerShell).~~  
  *Preuve / Contexte de validation :* 

- [ ] ~~**S11 — Niveaux de service (SLA) :** ententes de niveau de service, contrats d'assistance, indicateurs GTR/GTI, obligations de moyens et de résultats, pénalités associées.~~  
  *Preuve / Contexte de validation :* 

---

### Activité 1.3 : Développer la présence en ligne de l'organisation

- [ ] ~~**S12 — Technologies et programmation Web :** normes HTML/CSS, langages clients/serveurs, requêtage et manipulation de données, déploiement et paramétrage d'un CMS, conventions d'écriture et référencement (SEO).~~  
  *Preuve / Contexte de validation :* 

- [ ] ~~**S13 — Cadre économique et juridique du Web :** e-réputation d'une organisation, responsabilités respectives de l'éditeur et de l'hébergeur, mentions légales, conditions générales d'utilisation (CGU), conformité RGPD appliquée au web, droits sur les contenus et gestion des noms de domaine.~~  
  *Preuve / Contexte de validation :* 

---

### Activité 1.4 : Travailler en mode projet

- [ ] ~~**S14 — Gestion de projet :** principes de planification prédictive et séquentielle (cycle en V, diagramme de Gantt) vs démarches agiles (Scrum, Kanban, sprints, itérations).~~  
  *Preuve / Contexte de validation :* 

- [ ] ~~**S15 — Outils de suivi de projet :** environnements collaboratifs de gestion de tickets, tableaux de bord de projet, calcul des charges, indicateurs d'avancement et analyse des écarts.~~  
  *Preuve / Contexte de validation :* 

---

### Activité 1.5 : Mettre à disposition des utilisateurs un service informatique

- [x] **S16 — Architecture et déploiement de services :** composants structurels d'un service applicatif ou d'infrastructure, protocoles réseaux associés, techniques de paquetage logiciel et outils de distribution/déploiement.  
  *Preuve / Contexte de validation :* Déploiement de Graylog, OpenSearch et MongoDB en conteneurs avec Docker Compose — [fiche Graylog](https://timothy-valentin.github.io/realisations/centralisation-logs-graylog-opensearch/) ; services AD DS, DNS et DHCP — [fiche Réseau d'entreprise complet](https://timothy-valentin.github.io/realisations/reseau-entreprise-proxmox-ad-pfsense/).

- [ ] ~~**S17 — Validation et recette :** élaboration et réalisation de jeux d'essais, tests d'intégration et d'acceptation utilisateur, rédaction du procès-verbal de recette et support d'accompagnement au changement.~~  
  *Preuve / Contexte de validation :* 

---

### Activité 1.6 : Organiser son développement professionnel

- [x] **S18 — Veille et développement de carrière :** méthodologies de veille informationnelle et technologique, outils de curation et flux, gestion de son e-réputation et de son identité numérique professionnelle, techniques de valorisation de profil (CV, réseaux pro) et cartographie des métiers du numérique.  
  *Preuve / Contexte de validation :* Veille sur les passkeys, méthode de veille et fil d'actualités automatisé — [page Veille](https://timothy-valentin.github.io/veille/) ; identité professionnelle : [portfolio](https://timothy-valentin.github.io), [GitHub](https://github.com/Timothy-Valentin), [LinkedIn](https://www.linkedin.com/in/timothyvalentin/).
