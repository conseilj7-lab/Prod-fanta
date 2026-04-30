# 🎉 Tim Event — Application de Gestion Événementielle

## Installation sur iPhone (sans App Store)

1. Ouvrez `index.html` dans **Safari** sur votre iPhone
2. Appuyez sur le bouton **Partager** (carré avec ↑)
3. Sélectionnez **"Sur l'écran d'accueil"**
4. Appuyez **Ajouter** — l'icône Tim Event apparaît sur votre accueil

---

## Fonctionnalités

### 🏠 Tableau de bord
- Stats : CA mensuel, CA total, réservations actives, clients, alertes stock
- Prochaines réservations
- Alertes stock en temps réel
- Journal d'activité

### 📅 Calendrier
- Vue mensuelle des réservations
- Clic sur un jour pour voir les événements
- Indicateurs visuels (points dorés)

### 👥 CRM Clients
- Créer/modifier/supprimer des clients
- Nom, prénom, email, téléphone, adresse complète
- Historique réservations et documents liés
- Recherche instantanée

### 📋 Réservations
- Création avec sélection client + articles loués
- **Blocage automatique** si stock insuffisant ⚠️
- Alerte visuelle stock en temps réel lors de la saisie
- Statuts : confirmée / acompte / terminée / annulée
- Filtres par statut et recherche

### 📦 Gestion de Stock
- Stock initial fourni (chaises napoléoniennes, tables, etc.)
- Seuil d'alerte configurable par article
- Barre de progression visuelle
- Ajustement manuel (entrée / sortie / définir)
- Alertes automatiques tableau de bord

### 📄 Devis
- Lignes personnalisables avec tarifs préconfigurés
- Calcul TVA automatique
- Numérotation automatique (préfixe configurable)
- Convertible en facture en 1 clic
- Statuts : en attente / accepté / refusé

### 🧾 Factures
- Facture finale avec acompte déduit
- Reste à payer calculé automatiquement
- Reçu d'acompte séparé
- Envoi par Email ou WhatsApp

### 🗂️ Documents
- Tous les documents en un endroit
- Filtres par type (devis / facture / reçu)
- Lié au CRM client
- Prévisualisation PDF intégrée
- Bouton fermeture PDF (✕)

### 💰 Comptabilité (loi française)
- Journal des recettes
- **Calcul URSSAF automatique** pour Entreprise individuelle
- Taux : 22,1% (prestations de services)
- CSG/CRDS : 9,7%
- Versement libératoire IR (micro)
- Filtre par année et trimestre
- Rappel légal déclaration URSSAF

### ⚙️ Paramètres
- **Entreprise** : Nom, SIRET, APE, TVA intracommunautaire, RCS, IBAN, capital
- **Contact** : Email pro, téléphone, WhatsApp, site web, mentions légales
- **Tarifs** : Catalogue modifiable (ajout/suppression)
- **Application** : Préfixes, TVA, validité devis, % acompte, termes paiement
- Export / Import des données (sauvegarde JSON)

---

## Sécurité
- Sanitisation XSS sur toutes les entrées utilisateur
- Content Security Policy (CSP) configurée
- Validation SIRET, email, téléphone
- Pas d'envoi de données externes
- Stockage 100% local (localStorage)

## Documents — Maquette facture
- Logo Tim Event (T doré sur fond noir)
- En-tête avec coordonnées société
- Badge type document (DEVIS / FACTURE / REÇU D'ACOMPTE)
- Ligne dorée décorative
- Bloc client + informations événement
- Tableau des prestations
- Totaux avec gestion TVA
- Mention "TVA non applicable, art. 293 B du CGI" si EI sans TVA
- Pied de page avec SIRET

## Données initiales (stock)
- 200 Chaises napoléoniennes
- 30 Tables rectangulaires 180cm
- 20 Tables rondes 150cm
- 100 Nappages blancs
- 80 Nappages dorés
- 200 Housses de chaise blanches
- 300 Nœuds de chaise
- 3 Arches florales
- 2 Podiums scène
- 3 Sonos + micro HF
