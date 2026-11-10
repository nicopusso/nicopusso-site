# nicopusso.com

Sitio personal de Nico Pusso, en Astro. Se publica en Vercel desde `main`.

## Desarrollo

```
npm install
npm run dev
```

## Idiomas

Castellano en `/` e inglés en `/en/`. Las dos páginas usan el mismo componente (`src/components/Home.astro`); los textos están en `copy`. Los links a Porto van a su versión en el mismo idioma.

## Weekly Random

Las notas viven en porto.works/weekly-random. Este sitio no las duplica:

- La home muestra las tres últimas. Están en `src/components/Home.astro`, en `copy.es.notas` y `copy.en.notas` (título y bajada en cada idioma, sacados de porto-site) más su portada en `covers` y `src/assets/weekly-random/`. Al publicar una nueva en Porto, actualizar los dos idiomas.
- `vercel.json` redirige (301) las URLs del WordPress viejo a cada nota en Porto.
