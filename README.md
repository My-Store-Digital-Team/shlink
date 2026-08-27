# Shlink — acortador con QR nativo

- **Short URLs / API:** https://qr.yoany.link
- **Panel:** https://shlink.mystoredigital.cloud (shlink-web-client; el servidor y la API key se configuran en el navegador)
- **QR de cualquier enlace:** `https://qr.yoany.link/<slug>/qr-code?size=800&format=png`
- BD: SQLite en el volumen `shlink_data`. Sin secretos en este repo: la API key se genera con `shlink api-key:generate` dentro del contenedor.

Desplegado vía Dokploy (VPS mystoredigital) + Traefik + Let's Encrypt.
