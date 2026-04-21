# Stats Agents IA — AIDEO

Dashboards mensuels des agents IA en production, déployés chez les clients AIDEO.

## Clients actifs

- The Artist Academy → /clients/the-artist-academy/

## Architecture

- **Données** : récupérées chaque 1er du mois depuis l'API Voiceflow via un workflow n8n
- **Stockage** : fichiers JSON dans le dossier /data/, mis à jour automatiquement par n8n via l'API GitHub
- **Hébergement** : Cloudflare Pages (déploiement auto à chaque push)
- **Authentification** : Cloudflare Access (code à usage unique envoyé par email)

## Contact

Frédéric Ruault — AIDEO   f.ruault@ai-deo.fr
