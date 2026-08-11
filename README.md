# Guía abierta de la reforma a la LFPIORPI · ACUERDO 115/2026

Material de consulta gratuito sobre las nuevas Reglas de Carácter General de la Ley Federal
para la Prevención e Identificación de Operaciones con Recursos de Procedencia Ilícita,
publicadas en el Diario Oficial de la Federación el viernes 7 de agosto de 2026.

Publicado por **GMC360 · 360Educa · ASONOC**.

## Qué contiene

| Ruta | Contenido |
|---|---|
| `/` | **Autodiagnóstico de brecha.** Veintisiete preguntas, menos de treinta minutos. Devuelve calificación con semáforo, avance por bloque y los pendientes ordenados por criticidad, cada uno con su artículo y su fecha de exigibilidad. |
| `/guia/` | **Guía completa.** Panorama, calendario de exigibilidad con fundamento, definiciones, las diecisiete actividades vulnerables con sus umbrales, el articulado capítulo por capítulo, el sistema en seis bloques, la figura del Representante, siete errores de lectura frecuentes, calculadora de umbrales y ruta de trabajo. |

## Cómo está hecho

Dos archivos HTML. Sin dependencias externas, sin librerías, sin proceso de compilación,
sin base de datos y sin cookies. Todo ocurre en el navegador de quien lo consulta:
no se guarda ni se envía información a ningún servidor.

## Cómo se publica

No requiere build. Basta servir la carpeta como sitio estático.

**Netlify conectado a este repositorio**
- Build command: *vacío*
- Publish directory: `.`

**Netlify Drop, GitHub Pages, Cloudflare Pages, Vercel o cualquier hosting compartido**
- Sube la carpeta tal cual.

## Cómo se actualiza

- Las preguntas del autodiagnóstico están en la constante `P`, al inicio del bloque `<script>` de `index.html`.
- Los umbrales de la calculadora están en la constante `AV` de `guia/index.html`.
- El calendario, las definiciones y el articulado son HTML directo en `guia/index.html`.

Al modificar cualquier cifra o fecha hay que revisar también la nota de método del pie de página.

## Nota de método

Los artículos 1 a 26 del ACUERDO 115/2026 están cotejados contra el texto publicado en el
Diario Oficial de la Federación. Los artículos 27 a 51, los doce transitorios y los anexos
se citan del proyecto del 23 de julio de 2026 y su cotejo está en proceso; el sitio lo indica
expresamente donde corresponde.

Este material es de apoyo académico y no constituye asesoría legal ni dictamen para un caso
concreto.

---

Versión 1.0 · 11 de agosto de 2026
