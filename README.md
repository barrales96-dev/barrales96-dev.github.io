# Backend Node/Express para Fono+ (scaffold)

Este backend es un punto de partida para reemplazar el localStorage por API real.

## Ejecutar local
```bash
npm install
npm start
```

Endpoints principales:
- POST /api/login
- GET/POST /api/users
- GET /api/patients
- GET /api/dataset
- POST /api/phoneme-samples
- PATCH /api/phoneme-samples/:id/label

Para producción falta: variables de entorno, HTTPS, almacenamiento cloud, consentimiento, auditoría y políticas de privacidad.
