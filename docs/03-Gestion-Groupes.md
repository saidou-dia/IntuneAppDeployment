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

