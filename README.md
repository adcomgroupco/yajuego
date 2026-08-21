# YaJuego · Landing Pages de Consultoría

Sitio estático con entregables de consultoría digital para YaJuego.

## Estructura

- `index.html`: hub principal de acceso a todos los entregables.
- `resumen.html`: resumen ejecutivo de todo lo trabajado, con hallazgos clave y enlace a cada informe.
- `ruta.html`: ruta de pauta digital.
- `diagnostico-inicial.html`: diagnóstico inicial de performance.
- `auditoria-keywords.html`: auditoría de keywords y términos de búsqueda.
- `auditoria-gtm.html`: auditoría general de Google Tag Manager.
- `auditoria-gtm-plan-accion.html`: plan de acción GTM.
- `auditoria-ga4.html`: auditoría GA4 de fuente / medio, purchase y registro.
- `flow-mundial-top-view.html`: proyección de medios 3 meses Mundial 2026 + escenario TopView.
- `flow-ago-dic-influencers.html`: plan de medios ago–dic 2026 con Programmatic, TikTok e Influencers.
- `seguimiento-pauta.html`: informe de seguimiento de pauta embebido desde Looker Studio.
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
