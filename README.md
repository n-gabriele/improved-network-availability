# 📁 Amélioration de la disponibilité réseau avec Active Directory  
📘 Réalisé par : Nathan Gabriele – BTS SIO SISR

---

## 🎯 Objectif

Mettre en œuvre un **contrôle centralisé et sécurisé des ressources** via l’installation, la configuration et l’utilisation de **l’Active Directory (AD)**, tout en assurant une gestion rigoureuse des **droits de partage et des autorisations NTFS**.

---

## 🛠️ Composants mis en place

### 🏗️ Installation de l’Active Directory
- Déploiement de **Windows Server 2008 R2** en contrôleur de domaine
- Intégration des postes clients dans le domaine
- Création des **OU (Unités d’Organisation)** et **groupes d’utilisateurs** (étudiants, professeurs, administrateurs)

### 📂 Partages réseau
- Dossiers partagés : `individus`, `applications`, `ressources`
- Accès réseau configuré via **partage administré**
- Attribution des droits **Contrôle total** au groupe « Tout le monde » en partage

### 🔐 Sécurisation par NTFS
- Application de **droits NTFS spécifiques par groupe** :
  - **Administrateurs** : contrôle total
  - **Professeurs** : modification (sur certains dossiers)
  - **Étudiants** : lecture seule
- Désactivation de l’héritage des autorisations sur chaque dossier
- Attribution manuelle et ciblée des droits via la console de sécurité

### 💻 Tests utilisateurs
- Connexions réalisées avec des comptes différents (administrateur, professeurs, étudiants)
- Vérifications des autorisations élémentaires :
  - Lecture, écriture, suppression
  - Création de fichiers/dossiers
  - Modification des droits (interdite sauf pour admins)

---

## 🧠 Compétences mobilisées

- Déploiement et configuration d’un **contrôleur de domaine**
- Mise en œuvre d’une **architecture Active Directory fonctionnelle**
- Gestion des **droits d’accès utilisateurs via les stratégies de sécurité**
- Paramétrage des **autorisations de fichiers via NTFS**
- Tests de validation des droits dans un environnement client-serveur

---

## ✅ Résultat

Une **infrastructure stable et sécurisée** garantissant une meilleure **disponibilité des ressources**, une **gestion centralisée des accès** et une **maîtrise des permissions** selon les rôles utilisateurs.  
L’environnement est désormais prêt pour accueillir des partages collaboratifs avec des niveaux d’accès différenciés et contrôlés.

---

## 👨‍💻 Auteur

**Nathan Gabriele**  
📧 Contact : [votre.email@domaine.com]

---
