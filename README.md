# nicopusso.com

Sitio personal de Nico Pusso, en Astro. Se publica en Vercel desde `main`.

## Desarrollo

```
npm install
npm run dev
```

## Weekly Random

Las notas viven en porto.works/weekly-random. Este sitio no las duplica:

- La home muestra las tres últimas (lista `notas` en `src/pages/index.astro`). Al publicar una nueva en Porto, actualizar esa lista y su portada en `src/assets/weekly-random/`.
- `vercel.json` redirige (301) las URLs del WordPress viejo a cada nota en Porto.
