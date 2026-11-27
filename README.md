# YaJuego · Landing Pages de Consultoría

Sitio estático con entregables de consultoría digital para YaJuego.

## Estructura

- `index.html`: hub principal de acceso a todos los entregables.
- `diagnostico/resumen.html`: resumen ejecutivo de todo lo trabajado, con hallazgos clave y enlace a cada informe.
- `planeacion/ruta.html`: ruta de pauta digital.
- `diagnostico/inicial.html`: diagnóstico inicial de performance.
- `auditorias/keywords.html`: auditoría de keywords y términos de búsqueda.
- `auditorias/gtm.html`: auditoría general de Google Tag Manager.
- `auditorias/gtm-plan-accion.html`: plan de acción GTM.
- `auditorias/ga4.html`: auditoría GA4 de fuente / medio, purchase y registro.
- `planeacion/flow-mundial.html`: proyección de medios 3 meses Mundial 2026 + escenario TopView.
- `planeacion/flow-ago-dic.html`: plan de medios ago–dic 2026 con Programmatic, TikTok e Influencers.
- `influencers/roster.html`: roster de cuatro creadores de Instagram (de los nueve que propuso Management CM), por qué se descartó a los otros cinco y una reserva que completa $20 millones, con seguidores, interacción, calidad de audiencia y KPIs de inversión. Fotos en `assets/img/roster/`.
- `roster/<creador>.html`: una ficha por creador (rendimiento, audiencia, inversión estimada), enlazada desde el roster.
- `planeacion/seguimiento.html`: informe de seguimiento de pauta embebido desde Looker Studio.
- `assets/css/site.css`: estilos base compartidos por las landing pages.
- `assets/css/index.css`: estilos específicos del hub.
- `assets/css/resumen.css`: estilos específicos del resumen ejecutivo.
- `assets/css/seguimiento.css`: estilos específicos del informe de seguimiento.

## Convención visual

Las páginas funcionan como landing pages/reportes independientes:

- HTML en la raíz para mantener compatibilidad directa con GitHub Pages.
- Estilos comunes en `assets/css/site.css`.
- Estilos específicos cerca de cada documento cuando el reporte requiere tablas, gráficos o layouts propios.
- Índice lateral fijo en reportes extensos y tarjetas de navegación en el hub.
- Tipografía única en todo el sitio: **Poppins** (pesos 300–800 + itálica 400), cargada desde Google Fonts.


## Organización de documentos

La portada es [index.html](index.html). Cada carpeta agrupa un tema. Los nombres
usan minúsculas, guiones y fechas `AAAA-MM` o `AAAA-MM-DD` cuando distinguen cortes.
El nombre del cliente vive en el repositorio y no se repite en cada URL.
Los títulos de la portada y de cada documento usan el mismo nombre.

Los HTML en las rutas anteriores solo redirigen para conservar enlaces compartidos,
incluidos sus parámetros y secciones. Los documentos nuevos se guardan en las
carpetas temáticas y se enlazan desde la portada.

| Documento | Ruta |
|---|---|
| [Resumen general](diagnostico/resumen.html) | `diagnostico/resumen.html` |
| [Diagnóstico inicial](diagnostico/inicial.html) | `diagnostico/inicial.html` |
| [Inicio de pauta en TikTok](diagnostico/inicio-tiktok.html) | `diagnostico/inicio-tiktok.html` |
| [Auditoría de Google Ads](auditorias/google-ads.html) | `auditorias/google-ads.html` |
| [Google Ads Audit (English)](auditorias/google-ads-en.html) | `auditorias/google-ads-en.html` |
| [Auditoría de keywords](auditorias/keywords.html) | `auditorias/keywords.html` |
| [Auditoría general GTM](auditorias/gtm.html) | `auditorias/gtm.html` |
| [Plan de acción GTM](auditorias/gtm-plan-accion.html) | `auditorias/gtm-plan-accion.html` |
| [Auditoría GA4](auditorias/ga4.html) | `auditorias/ga4.html` |
| [Ruta de pauta digital](planeacion/ruta.html) | `planeacion/ruta.html` |
| [Flow Mundial + TopView](planeacion/flow-mundial.html) | `planeacion/flow-mundial.html` |
| [Flow Ago-Dic + Influencers](planeacion/flow-ago-dic.html) | `planeacion/flow-ago-dic.html` |
| [Informe de programática](planeacion/programatica.html) | `planeacion/programatica.html` |
| [Seguimiento de pauta](planeacion/seguimiento.html) | `planeacion/seguimiento.html` |
| [Roster de influencers](influencers/roster.html) | `influencers/roster.html` |
| [Cotización del roster](influencers/cotizacion.html) | `influencers/cotizacion.html` |
| [Camilo Bermudez](influencers/creadores/el_bermu09.html) | `influencers/creadores/el_bermu09.html` |
| [El Gonchi](influencers/creadores/elgonchi.html) | `influencers/creadores/elgonchi.html` |
| [Felipe Piedrahita](influencers/creadores/soypipefutbol.html) | `influencers/creadores/soypipefutbol.html` |
| [Carlos Martinez](influencers/creadores/uncalenoporahi.html) | `influencers/creadores/uncalenoporahi.html` |
