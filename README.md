# Torque Systems — Landing Page

Point de départ pour le site web de Torque Systems.

## Statut

**v2.0** — Version dé-sectorisée + voix fondateur (février 2026)

## Historique des versions

| Version | Date | Changements |
|---------|------|-------------|
| v1.0 | Fév 2026 | Version initiale |
| v2.0 | Fév 2026 | Dé-sectorisé, intégration IA, voix fondateur "Je" |

## Contenu

- `index.html` — Landing page single-file (HTML + CSS + JS inline)

## Caractéristiques v2

- **Hero** : "Vos relances, rappels et documents gérés par l'IA. Pas par vous."
- **Badge** : "Automatisation IA pour PME · Île-de-France"
- **Voix** : Fondateur "Je" (personnel) au lieu de "Nous" (agence)
- **Stats** : 24/7 · ~30€/mois infra · 100% vos données
- **4 cas d'usage universels** : Relances & recouvrement, Collecte docs, Rappels & confirmations, Suivi & reporting
- **Section Fondateur** : Gabriel, bio, credentials
- **Programme Pilote** : Section dark slate, places limitées printemps 2026
- **Modèle client-hosted** : Tableau comparatif Zapier/Agence/Torque
- **Pricing simplifié** : "À partir de" + badge "Le plus choisi"
- **FAQ** : 6 objections traitées
- **CTA final** : Fond bleu, bouton blanc (inversé vs v1)
- **Footer** : hello@torquesystems.io + Mentions légales

## Stack technique

- Single-file HTML (zéro dépendance sauf Google Fonts)
- Fonts : DM Sans (titres) + Instrument Sans (corps, remplace Inter)
- Couleurs : Slate Black `#0F172A` · Trust Blue `#1E40AF` · White `#FFFFFF`
- Responsive (breakpoints 900px, 600px)
- Nav links : Solutions · Méthode · Tarifs · FAQ
- Animations scroll reveal (IntersectionObserver, `{ passive: true }`)
- FAQ accordion vanilla JS
- `@media print` : `@page`, `break-inside: avoid`, reveal override, `color: #000`

## Règles de contenu

| Dire | Ne PAS dire |
|------|-------------|
| IA, système intelligent, sur mesure | workflow, automatisation, n8n, API, no-code |
| dirigeant, entreprise | cabinet médical, comptable, dentiste, artisan |

## Déploiement futur

Ce fichier est prêt pour un déploiement Vercel/Netlify en 1 clic.

---

© 2026 Torque Systems
