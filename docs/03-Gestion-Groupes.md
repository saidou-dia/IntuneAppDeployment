# 03 - Création et gestion des groupes utilisateurs et appareils

Avant de déployer une application, il faut définir qui va la recevoir : utilisateurs ou appareils ciblés.

## Accès au portail
- Ouvrir un navigateur web et se connecter à [Intune Portal](https://endpoint.microsoft.com)
- Menu : Groupes → Tous les groupes → Nouveau groupe

## Créer un nouveau groupe
- Type : Sécurité (pour déploiement apps)
- Appartenance : Statique ou Dynamique
- Cible : Utilisateur ou Appareil

### Exemple
| Type    | Description                           | Exemple                  |
|---------|---------------------------------------|--------------------------|
| Utilisateur | Regroupe comptes utilisateurs       | Employés du siège        |
| Appareil   | Regroupe postes gérés par Intune     | Postes Windows 11        |

## Règles dynamiques
- Ajouter automatiquement les membres selon filtre (ex: tous les PC Windows 11 Pro)
- Valider la règle avant enregistrement

### Récapitulatif
- Groupe utilisateurs : gestion automatique comptes de test
- Groupe appareils : affectation automatique des postes

3. Création et gestion des groupes utilisateurs et appareils 

Avant de déployer une application, il faut définir qui va la recevoir : les utilisateurs ou les appareils ciblés. 

3.1. Accès au portail 

Ouvrir un navigateur web. 

Se connecter à https://endpoint.microsoft.com. 

Dans le menu de gauche, cliquer sur Groupes → Tous les groupes → Nouveau groupe. 

 

 

 

3.2. Créer un nouveau groupe 

Dans le menu de gauche, clique sur Groupes. 

Clique sur Tous les groupes. 

Clique sur Nouveau groupe. 

 

 

 

 

Type de groupe 

Description 

Exemple 

Utilisateur 

Regroupe des comptes d’utilisateurs. 

Groupe “Employés du siège”. 

Appareil 

Regroupe des ordinateurs gérés par Intune. 

Groupe “Postes Windows 11”. 

 

 

 

 

 

 

3.3. Définir le type de groupe 

Type de groupe : 

Sécurité si le groupe est pour le déploiement d’applications. 

Type d’appartenance : 

Dynamique pour que les membres soient ajoutés automatiquement via une règle. 

Type de groupe cible : 

Utilisateur dynamique si tu veux déployer l’appli selon les comptes utilisateurs. 

Appareil dynamique si tu veux déployer l’appli selon les postes (recommandé pour les Win32/M365). 

 

 

 

Type 

Fonctionnement 

Exemple 

Statique 

Ajout manuel des membres. 

Tu choisis chaque utilisateur. 

Dynamique 

Ajout automatique selon une règle (filtre). 

Tous les PC sous Windows 11 Pro. 

 

3.4. Configurer la règle dynamique 

 

Configurer la règle pour les devices de test  

 

Valider la règle pour les devices de test, Vérifie que la règle est correcte et clique sur Enregistrer. 

 

Récapitulatif des groupes de tests crées 

Un pour les utilisateurs, afin de gérer automatiquement les comptes de test. 

Un pour les appareils, afin de gérer automatiquement l’affectation de postes 

 
