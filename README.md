# Proxy Vercel vers Hosting PHP

## Configuration Cloudflare (Important)
Pour que le cache fonctionne et épargne votre serveur :
1. Allez dans **Caching** > **Configuration** sur Cloudflare.
2. Créez une **Page Rule** ou utilisez **Cache Rules**.
3. Ciblez l'URL de votre hosting ou tous les URLs.
4. Réglez **Cache Level** sur **Cache Everything**.
5. Réglez **Edge TTL** sur **1 year**.

## Domaines configurés
- `i.cinmov.com`
- `vip.cinmov.com`
- `fr.cinmov.com`
- `www.cinmov.com`
- `cinmov.com`
