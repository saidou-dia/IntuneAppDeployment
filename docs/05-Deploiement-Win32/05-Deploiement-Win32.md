# 05 - Déploiement d’une application Win32

## Objectif
Installer des applications personnalisées ou non présentes sur le Store (ex : MicroSIP, 7-Zip, VLC).

## Étapes

### A. Préparation du package
1. Télécharger setup (.exe/.msi)
2. Créer dossier de référence (ex: `C:\IntuneApps\Chrome`)
3. Convertir en `.intunewin` via IntuneWinAppUtil.exe

### B. Déploiement dans Intune
1. Portail Intune → Applications → Ajouter → Win32
2. Importer fichier `.intunewin`
3. Renseigner informations (Nom, Editeur, Description)
4. Définir commandes installation/désinstallation silencieuse
5. Configurer codes retour et règles de détection
6. Affecter au groupe de test (utilisateur ou appareil dynamique)

### Suivi
- Vérifier installation sur poste test
- Consulter logs : `C:\ProgramData\Microsoft\IntuneManagementExtension\Logs`
