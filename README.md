# El Gran Reacomodo

Sitio estático (HTML + JS, sin build) con las proyecciones de población del DANE.

## Archivos

- `index.html` — la aplicación completa.
- `dane-population.js` — datos de población (`DANE_POP`).
- `vercel.json` — configuración de despliegue.

## Local

```bash
npx serve .
```

## Despliegue en Vercel

1. Importar este repo en Vercel (**Add New → Project**).
2. Framework Preset: **Other**. Sin comando de build; Output Directory: raíz (`.`).
3. Deploy. Cada push a `main` despliega a producción.
