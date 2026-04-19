# Panel de Consumo Eléctrico ⚡

Panel web en tiempo real que muestra el consumo eléctrico mensual por persona.

## Características

- Datos en vivo desde Google Sheets (se refresca cada 5 minutos automáticamente)
- Gráfico de línea — evolución de kWh mensual
- Gráfico de barras — monto total por mes
- Gráfico de dona — distribución del último mes (Papa / Vero / Hans)
- Gráfico de barras apiladas — histórico de pagos por persona
- Tabla completa con todos los meses

## Fuente de datos

Google Sheets ID: `1004pnx79NdTrqDrr5ukJpru5sUtXoi6yOxKzF-x0y64`

> El sheet debe estar publicado en la web como CSV:
> **Archivo → Compartir → Publicar en la web → CSV**

## Publicar en GitHub Pages

```bash
git init
git add .
git commit -m "panel electricidad"
git branch -M main
git remote add origin https://github.com/TU_USUARIO/electricidad.git
git push -u origin main
```

Luego en GitHub: **Settings → Pages → Source: main → / (root) → Save**

URL pública: `https://TU_USUARIO.github.io/electricidad/`

## Tecnologías

- HTML + CSS puro (sin frameworks)
- Chart.js (CDN)
- Google Sheets CSV export (datos en vivo)
