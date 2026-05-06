# MBR Collections — Abril 2026

Monthly Business Review del equipo de Collections de Alegra, correspondiente al período **Abril 2026 vs. Marzo 2026**.

## Contenido

El reporte incluye:

1. **Recaudo USD** — Resultados GLO, Core y Lite con comparación vs año anterior (2025) y variación mensual
2. **Eficiencia Transaccional (NSM)** — Performance vs target ≥ 90% por país y segmento
3. **So What** — Análisis cualitativo de los resultados del mes
4. **Now What** — Plan de acción del equipo
5. **Análisis Adicionales** — Revenue Bridge Mar vs Abr 2026 y Proyección Mayo 2026

## Estructura del repositorio

```
/
├── index.html    # MBR completo (autocontenido, sin dependencias externas)
└── README.md     # Este archivo
```

## Despliegue

Este repositorio está configurado para desplegarse automáticamente en **Vercel**.

- El archivo `index.html` en la raíz es servido como página principal.
- No requiere build steps ni frameworks — es HTML estático puro.
- Las gráficas son SVG inline codificadas en base64, sin dependencia de CDNs ni archivos externos.

### Deploy manual en Vercel

1. Conecta este repositorio en [vercel.com](https://vercel.com)
2. Framework Preset: **Other**
3. Build Command: *(vacío)*
4. Output Directory: `.` (raíz)
5. Click **Deploy**

## Notas técnicas

- **Gmail-compatible**: CSS 100% inline, layout en tablas, sin flexbox/grid
- **Sin dependencias externas** para las gráficas: SVG inline base64
- **Logo Alegra**: cargado desde Google Drive (requiere conexión a internet)
- Generado con el estándar visual **QBR/MBR Generator v17** de Alegra

## Autor

**Mario Valdez Arias** — Collection Data Analyst  
alegra.com
