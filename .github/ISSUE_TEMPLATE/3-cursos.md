---
title: 'Ruta cursos (GET /cursos)'
labels: auto-issue
---

# Requisito: Ruta /cursos

Deberás implementar la ruta `/cursos` que responda con el mensaje:
`"Te interesan nuestros cursos. Vení a conocer la oferta!"`

El servidor debe retornar un código de estado `200` y definir los encabezados `Content-Type: text/plain` con `charset=utf-8`.

Este requisito se validará ejecutando:

```bash
npm test -- -t "GET /cursos debería devolver"
```
