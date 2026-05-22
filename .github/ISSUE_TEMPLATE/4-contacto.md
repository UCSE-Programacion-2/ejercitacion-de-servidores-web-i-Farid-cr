---
title: 'Ruta contacto (GET /contacto)'
labels: auto-issue
---

# Requisito: Ruta /contacto

Deberás implementar la ruta `/contacto` que responda con el mensaje:
`"Si querés contactarnos, hacelo a este Email: :)"`

El servidor debe retornar un código de estado `200` y definir los encabezados `Content-Type: text/plain` con `charset=utf-8`.

Este requisito se validará ejecutando:

```bash
npm test -- -t "GET /contacto debería devolver"
```
