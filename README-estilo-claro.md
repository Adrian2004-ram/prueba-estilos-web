# SportMeet - Guía de estilo, versión clara

Este documento describe la versión clara de la interfaz, pensada como una base realista para un proyecto web de eventos deportivos con foco en confianza, claridad y conversión.

## Objetivo visual

La versión clara transmite una marca profesional, limpia y dinámica. Usa fondos luminosos, tarjetas blancas, sombras suaves y acentos azules y naranjas para guiar la atención hacia las acciones principales.

## Fuentes

La versión clara carga dos tipografías desde Google Fonts:

| Fuente | Uso |
| --- | --- |
| Barlow | Texto general, párrafos, información secundaria y contenido funcional. |
| Teko | Titulares, botones, elementos de marca y llamadas a la acción. |

## Paleta de color

La paleta está definida en variables CSS dentro de [css/styles.css](css/styles.css).

| Variable | Color | Uso recomendado |
| --- | --- | --- |
| --primary | #1e3a8a | Color principal de marca. Se usa en detalles visuales, etiquetas y elementos de énfasis sobrios. |
| --primary-light | #3b82f6 | Variante luminosa del color principal. Ideal para degradados, marca y componentes destacados. |
| --accent | #f97316 | Color de acción secundaria. Funciona bien para botones de conversión y elementos que requieren contraste cálido. |
| --danger | #b91c1c | Estado de alerta o urgencia. Se usa en etiquetas, avisos y señales de riesgo. |
| --ink | #0b0f19 | Texto muy oscuro para contrastes fuertes y títulos sobre fondos claros. |
| --bg | #f9fafb | Fondo base de la página. Aporta limpieza y neutralidad. |
| --text | #111827 | Color principal de texto. Pensado para legibilidad en contenido largo. |
| --muted | #6b7280 | Texto secundario, metadatos, ayudas visuales y descripciones. |
| --success | #22c55e | Estado positivo o disponible. Se usa para cupos abiertos, confirmaciones y mensajes de éxito. |
| --line | #dbe2ea | Bordes, separadores, tarjetas y contenedores secundarios. |
| --card | #ffffff | Superficie principal de tarjetas y bloques de contenido. |

## Roles de color en la interfaz

La distribución de color sigue una lógica de producto real:

| Zona | Color o recurso | Función |
| --- | --- | --- |
| Fondo general | Degradado radial con --bg y azules muy claros | Da profundidad sin romper la sensación limpia de una app moderna. |
| Encabezado | Gradiente oscuro con azul de marca | Refuerza identidad y separación visual respecto al contenido. |
| Logo | Degradado con --primary y --primary-light | Sirve como marca rápida y reconocible. |
| Botón principal | Fondo oscuro con sombra | Prioriza la acción principal sin depender solo del color de acento. |
| Botón de conversión | Gradiente naranja y rojo | Activa la acción más comercial o inmediata. |
| Tarjetas | Fondo blanco y borde suave | Mantiene el foco en contenido y lectura rápida. |
| Estado abierto | Verde | Comunicación positiva y clara de disponibilidad. |
| Estado con pocas plazas | Rojo suave | Genera urgencia sin ser agresivo. |
| Estado cerrado o finalizado | Gris neutro | Reduce protagonismo de elementos no accionables. |

## Componentes principales

La versión clara está organizada en bloques listos para reutilizar en un proyecto real:

- Barra superior con navegación y acceso al panel.
- Hero principal con mensaje de valor, acciones y métricas.
- Tarjeta destacada para el próximo evento.
- Grid de eventos para catálogo.
- Bloque de confianza con argumentos de producto.
- Vista administrativa tipo CRUD, pensada para backend real.

## Reglas de uso

- Usa Barlow para todo lo que sea lectura continua o datos funcionales.
- Usa Teko para titulares, botones y piezas de marca con personalidad.
- Usa --primary para identidad y navegación, no para saturar toda la pantalla.
- Usa --accent para una única acción secundaria destacada por vista.
- Usa --danger y --success solo para estados; no los uses como colores decorativos generales.
- Mantén tarjetas claras y bordes suaves para conservar la sensación de producto profesional.

## Aplicación práctica

Esta versión encaja bien en:

- plataformas de reservas y eventos deportivos,
- paneles de administración ligeros,
- landing pages orientadas a conversión,
- productos SaaS con una estética cercana y confiable.

## Archivos relacionados

- [index.html](index.html)
- [css/styles.css](css/styles.css)
- [pages/crud-eventos.html](pages/crud-eventos.html)
