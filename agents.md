# AGENTS.md

Este repositorio contiene un currículum personal en HTML. El objetivo real del proyecto no es construir una web genérica, sino mantener una plantilla de CV que pueda exportarse a PDF y verse bien en un folio DIN A4.

## Objetivo Principal

El HTML y el CSS deben estar estructurados para imprimir o exportar el currículum en formato DIN A4 con buena calidad visual, márgenes controlados y sin cortes inesperados.

Antes de hacer cambios, prioriza siempre:

- Que el resultado sea legible y profesional en PDF.
- Que el contenido encaje correctamente en DIN A4.
- Que la versión impresa tenga prioridad sobre la vista web.
- Que la estructura HTML sea clara, semántica y fácil de mantener.

## Reglas Para Cambios En HTML/CSS

- Diseña pensando primero en impresión: `@page`, `@media print`, tamaños en `mm`, `cm` o unidades estables cuando tenga sentido.
- Mantén una anchura compatible con DIN A4 y evita layouts que dependan demasiado del viewport.
- Evita efectos puramente web que no aporten al PDF, como animaciones, fondos complejos, sombras excesivas o interacciones.
- Controla saltos de página con propiedades como `break-inside`, `page-break-inside`, `break-before` y `break-after` cuando sea necesario.
- Evita que se corten secciones, títulos, fechas, listas o bloques de experiencia entre páginas.
- Usa tipografías, tamaños, interlineados y espaciados pensados para lectura en papel.
- Comprueba que los colores tengan suficiente contraste al imprimirse o exportarse.
- No añadas dependencias pesadas si el mismo resultado puede conseguirse con HTML y CSS simples.

## Criterios De Aceptación

Un cambio debe considerarse correcto si:

- El CV puede abrirse en el navegador y exportarse a PDF en DIN A4.
- La impresión no introduce scroll horizontal, recortes laterales ni desbordamientos.
- Las secciones principales se ven ordenadas y con jerarquía clara.
- El diseño mantiene buen aspecto tanto en pantalla como en vista previa de impresión.
- El contenido importante no queda oculto ni separado de forma confusa por saltos de página.

## Verificación Recomendada

Después de cambios relevantes, revisa:

1. Vista normal en navegador.
2. Vista previa de impresión.
3. Exportación a PDF con tamaño de papel DIN A4.
4. Márgenes, saltos de página, legibilidad y alineación general.

Si hay conflicto entre estética web y resultado PDF, debe prevalecer el resultado PDF en DIN A4.
