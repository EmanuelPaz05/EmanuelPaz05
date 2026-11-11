# Coloquio integrador — Perfil profesional

**Emanuel Paz · Tecnicatura en Desarrollo de Software · 2026**

## Entregables

| Requisito | Recurso |
| --- | --- |
| Perfil profesional | [Portfolio](https://emanuel-paz-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/emapaz05/) |
| Proyecto principal | [Net-Gestión (sitio comercial)](https://netgestion.ar/) · [Caso de estudio](https://emanuel-paz-portfolio.vercel.app/proyectos/netgestion.html) |
| Repositorio público del proyecto principal | [Demo académica de Net-Gestión](https://github.com/EmanuelPaz05/Sistema-de-Gestion-de-Stock-para-Negocios) |
| Automatización ejecutable | [Reportes comerciales por correo (demo autónoma)](https://github.com/EmanuelPaz05/Sistema-de-Gestion-de-Stock-para-Negocios/tree/main/automatizacion-reportes) — genera reportes ficticios en JSON/HTML y permite envío opcional mediante Resend. |
| Documentación técnica | [README del proyecto grande](https://github.com/EmanuelPaz05/Sistema-de-Gestion-de-Stock-para-Negocios#readme) · [README de la automatización](https://github.com/EmanuelPaz05/Sistema-de-Gestion-de-Stock-para-Negocios/blob/main/automatizacion-reportes/README.md) |

> El producto comercial Net-Gestión y las demos académicas son implementaciones distintas. La demo pública y la automatización viven en carpetas separadas de **un mismo repositorio**; falta separarlas en dos repositorios GitHub distintos para cumplir literalmente ese requisito de la consigna. No incluyen datos ni código de producción.

## Guion oral de 5 minutos

### 0:00–1:30 · Presentación profesional
«Soy Emanuel Paz, desarrollador Full Stack de Córdoba. Trabajo en GoodApps y también desarrollo soluciones desde NetSol. Mi enfoque es escuchar necesidades de clientes y convertirlas en herramientas prácticas para negocios e instituciones. Trabajo con React, Node.js, PHP y bases de datos como MySQL».

### 1:30–3:00 · Proyecto grande: Net-Gestión
- **Problema:** un comercio necesita controlar ventas, stock, caja y cuentas corrientes.
- **Solución:** un producto de gestión comercial en uso por más de 30 clientes reales.
- **Recorrido:** abrir [netgestion.ar](https://netgestion.ar/), mostrar una pantalla del sistema con datos aptos para demostración y explicar un flujo comercial.
- **Respaldo de código público:** enseñar el repositorio de demo académica y su arquitectura Node.js / API / interfaz / reglas de negocio.

### 3:00–4:15 · Automatización real: Net-Gestión
- **Casos implementados:** facturación ARCA, integración Tiendanube, reportes automáticos por Gmail y correos con Resend en Net-Gestión.
- **Caso recomendado para explicar:** un reporte enviado automáticamente por correo, precisando el disparador real, el contenido y cómo se comprueba el envío.
- **Automatización ejecutable:** [Reportes por correo](https://github.com/EmanuelPaz05/Sistema-de-Gestion-de-Stock-para-Negocios/tree/main/automatizacion-reportes) — genera JSON/HTML desde ventas ficticias; envío externo desactivado por defecto.
- **Ejecutar:** desde `automatizacion-reportes`, `npm start -- --date=2026-11-11` y abrir `output/reporte.html`.
- **Documento técnico de integraciones reales:** [Automatizaciones de Net-Gestión](https://github.com/EmanuelPaz05/Sistema-de-Gestion-de-Stock-para-Negocios/blob/main/docs/automatizaciones-netgestion.md).
- **Advertencia:** la demo de reportes es una reimplementación educativa; no asegura la misma arquitectura de producción ni implementa ARCA, Tiendanube o Gmail. Resend es opcional con credenciales de prueba.

### 4:15–4:45 · Activos profesionales
Mostrar README de GitHub y enlaces al portfolio, LinkedIn y repositorios.

### 4:45–5:00 · Cierre
«Me interesa seguir creando software que resuelva necesidades reales. Mi experiencia combina desarrollo técnico, relación con clientes y mejora continua de productos».

## Validaciones antes de rendir

- [ ] Separar `automatizacion-reportes/` en un repositorio público propio y fijarlo junto a Net-Gestión desde «Customize your pins».
- [ ] Ejecutar `npm test` y `npm start` en la demo Net-Gestión.
- [ ] Desde `automatizacion-reportes/`, ejecutar `npm test` y `npm start -- --date=2026-11-11`, comprobando `output/reporte.html`.
- [ ] Agregar la automatización de reportes, capturas de ambos proyectos y enlaces al portfolio de Vercel.
- [ ] Confirmar que el PDF del CV técnico tenga enlaces correctos.
- [ ] Ensayar el recorrido cronometrado y entregar enlaces/PDF antes del coloquio.

*Esta guía prepara el coloquio; no constituye una certificación de que las demos hayan sido ejecutadas o que los repositorios estén fijados.*
