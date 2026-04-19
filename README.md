# n8n Email Automation

Automatisation d'envoi d'emails avec n8n à partir d'une liste Google Sheets.

## Fonctionnalités
- Lecture des lignes depuis Google Sheets
- Filtrage des emails valides
- Envoi automatique via Gmail
- Mise à jour du statut dans Google Sheets

## Workflow
Le fichier principal du workflow est :

- `workflow.json`

## Stack
- n8n
- Google Sheets
- Gmail

## Utilisation
1. Importer `workflow.json` dans n8n
2. Configurer les credentials Google Sheets et Gmail
3. Vérifier les colonnes du fichier Google Sheets :
   - Nom de l'Entreprise
   - Email
   - Statut
   - row_number
4. Lancer le workflow

## Statuts utilisés
- `En attente`
- `Envoyé`