---
title: 'Ruta raíz (GET /)'
labels: auto-issue
---

# Requisito: Ruta raíz

Deberás implementar un servidor HTTP usando Node.js que responda en la ruta raíz (`/`) con el mensaje:
`"Bienvenid@s! Gracias por tu visita."`

El servidor debe retornar un código de estado `200` y definir los encabezados `Content-Type: text/plain` con `charset=utf-8`.

Este requisito se validará ejecutando:

```bash
npm test -- -t "GET / debería devolver"
```
