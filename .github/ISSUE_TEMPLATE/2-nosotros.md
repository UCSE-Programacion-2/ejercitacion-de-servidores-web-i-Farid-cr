---
title: 'Ruta nosotros (GET /nosotros)'
labels: auto-issue
---

# Requisito: Ruta /nosotros

Deberás implementar la ruta `/nosotros` que responda con el mensaje:
`"Bienvenid@s a saber + de nosotros :)"`

El servidor debe retornar un código de estado `200` y definir los encabezados `Content-Type: text/plain` con `charset=utf-8`.

Este requisito se validará ejecutando:

```bash
npm test -- -t "GET /nosotros debería devolver"
```
