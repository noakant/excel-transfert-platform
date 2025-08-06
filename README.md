# Plateforme de Transfert Excel

Une application React moderne pour transférer et transformer des données entre fichiers Excel avec stockage sécurisé dans Supabase.

## Fonctionnalités

- 📊 Upload et traitement de fichiers Excel (.xlsx, .xls)
- 🔄 Mapping intelligent entre colonnes source et destination
- 🎯 Transformations de données (majuscules, minuscules, remplacement, valeurs manuelles)
- 👀 Prévisualisation en temps réel des transformations
- 💾 Sauvegarde des configurations de mapping
- 📚 Historique complet des opérations
- 🔐 Authentification utilisateur sécurisée
- 🗄️ Stockage persistant avec Supabase

## Installation

1. Clonez le repository
2. Installez les dépendances : `npm install`
3. Configurez Supabase :
   - Créez un projet Supabase
   - Copiez `.env.example` vers `.env`
   - Ajoutez vos clés Supabase
4. Lancez l'application : `npm run dev`

## Configuration Supabase

Exécutez les migrations SQL dans le dossier `supabase/migrations/` pour créer les tables nécessaires.

## Technologies

- React 18 + TypeScript
- Vite
- Tailwind CSS
- Supabase
- XLSX.js
- Lucide React Icons

## Licence

MIT
