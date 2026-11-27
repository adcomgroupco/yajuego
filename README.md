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
- `influencers/creadores/<creador>.html`: una ficha por creador (rendimiento, audiencia, inversión estimada), enlazada desde el roster.
- `planeacion/seguimiento.html`: informe de seguimiento de pauta embebido desde Looker Studio.
- `planeacion/programatica.html`: informe de programática, generado desde `data/input/yajuego/` con Media Bridge.
- `assets/css/adcom-v2.css`, `assets/ds/`, `assets/logos/`: el kit de diseño v2 de Adcom (copias: no se editan aquí).
- `assets/css/resumen.css`, `seguimiento.css`: estilos propios de esos dos informes.
- `assets/css/site.css`, `index.css`, `adcom.css`, `adcom-tokens.css` y `assets/js/adcom.js`: restos del sistema anterior (amarillo, Poppins). Ninguna página migrada los carga; se pueden retirar cuando `programatica.html` también esté en v2.

## Convención visual

Este repo usa el **sistema de diseño v2** de Adcom: fondo claro (washi), texto sumi, un solo acento lima,
Inter Tight e Inter con fuentes locales y el wordmark oficial. La regla completa es
[`ESTANDARES-DISENO.md`](ESTANDARES-DISENO.md); la galería de componentes, `banco-formatos/componentes.html`.

- Cada documento es una página independiente dentro de su carpeta temática (`diagnostico/`, `auditorias/`,
  `planeacion/`, `influencers/`); las rutas anteriores en la raíz solo redirigen.
- La lima es relleno con texto sumi (lo que se pulsa y lo primero de cada bloque), nunca texto ni línea.
- Verificación: `python -I herramientas/auditar_v2.py` desde la raíz del repo.


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
