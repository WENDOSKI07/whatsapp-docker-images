
# WhatsApp Web Clone – Deploy rápido y limpio

Imágenes ya subidas y probadas en:
→ https://ghcr.io/wendoski07/proyectows-backend:latest
→ https://ghcr.io/wendoski07/proyectows-frontend:latest

## Levantar en cualquier PC/servidor (1 minuto)

```bash
git clone https://github.com/WENDOSKI07/whatsapp-docker-images.git
cd whatsapp-docker-images

# Copiar variables de entorno
cp .env.example .env
# → Edita .env si quieres cambiar contraseñas o JWT

# Levantar todo
docker compose up -d --pull always
```
Release 26-11-2025 – Arreglé login y sesiones
Release 28-11-2025 – Fix @lid y newsletters + estabilidad total
