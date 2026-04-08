# SportMeet - Guía de estilo, versión oscura

Este documento describe la versión oscura de la interfaz, pensada como una alternativa más intensa, deportiva y publicitaria para un producto orientado a eventos y reservas rápidas.

## Objetivo visual

La versión oscura apuesta por contraste alto, bloques compactos, degradados profundos y una presencia visual más agresiva. Está diseñada para dar sensación de ritmo, urgencia y energía competitiva.

## Fuentes

La versión oscura carga dos tipografías desde Google Fonts:

| Fuente | Uso |
| --- | --- |
| Barlow | Texto base, descripciones, información de soporte y lectura general. |
| Anton | Titulares, botones, módulos de impacto, ticker y etiquetas de alto énfasis. |

## Paleta de color

La paleta está definida en variables CSS dentro de [css/styles-v2.css](css/styles-v2.css).

| Variable | Color | Uso recomendado |
| --- | --- | --- |
| --bg | #0b0f17 | Fondo general oscuro. Sirve como base de toda la experiencia. |
| --ink | #f3f6fc | Texto principal sobre fondos oscuros. Debe reservarse para contenido esencial. |
| --muted | #94a3b8 | Texto secundario, metadatos y jerarquía baja. |
| --red | #dc2626 | Color principal de acción e identidad. Funciona como tono de urgencia y deporte. |
| --red-strong | #be123c | Variante más intensa para acentos, hover o jerarquías críticas. |
| --line | #2b3447 | Bordes, separadores y contornos en superficies oscuras. |
| --panel | #151c2b | Fondo de paneles y contenedores internos. |

## Roles de color en la interfaz

La lógica visual de la versión oscura está distribuida para crear una interfaz compacta y potente:

| Zona | Color o recurso | Función |
| --- | --- | --- |
| Fondo general | Degradado radial oscuro | Genera profundidad y foco sobre el contenido. |
| Grain overlay | Punteado sutil blanco | Añade textura y evita que el fondo se vea plano. |
| Topbar | Negro azulado con bordes oscuros | Aporta sensación editorial y de noticia en tiempo real. |
| Navegación principal | Panel translúcido oscuro | Separa navegación y contenido sin perder integración. |
| Hero | Degradado entre azules oscuros y grafito | Crea una zona de impacto y presentación del mensaje principal. |
| Kicker y etiquetas | Rojo | Marca urgencia, categoría y energía competitiva. |
| CTA principal | Degradado rojo intenso | Refuerza la acción inmediata. |
| CTA secundario | Gris muy oscuro | Mantiene jerarquía sin competir con el CTA principal. |
| Tarjetas de evento | Degradados oscuros con variantes rojo y azul | Diferencia tipos de contenido sin perder cohesión visual. |
| Panel CRUD | Fondos oscuros con bordes fríos | Simula una consola de administración lista para backend real. |
| Estados y acentos | Rosa suave, verde claro y grises | Aportan variedad funcional para estados, disponibilidad y confirmación. |

## Componentes principales

La versión oscura se organiza en módulos que recuerdan a un dashboard editorial o deportivo:

- barra superior con aviso en tiempo real,
- navegación compacta tipo consola,
- hero de alto contraste con foco en conversión,
- ticker animado con mensajes de catálogo,
- grid de eventos con tarjetas diferenciadas,
- bloque CRUD con aspecto de backoffice.

## Reglas de uso

- Usa Anton solo donde necesites impacto visual real, no en todo el contenido.
- Usa Barlow para mantener legibilidad en descripciones, listas y formularios.
- Usa --red como color dominante de acción y marca, pero acompáñalo de grises oscuros para no saturar.
- Usa --muted para texto secundario y nunca para contenido crítico.
- Usa paneles oscuros y bordes fríos para que la interfaz conserve sensación de producto técnico.
- Reserva los degradados intensos para zonas clave; si todo destaca, nada destaca.

## Aplicación práctica

Esta versión encaja bien en:

- productos deportivos con tono de competición,
- webs de eventos con campañas activas,
- dashboards de gestión con identidad fuerte,
- landing pages con mensaje directo y agresivo.

## Archivos relacionados

- [index-v2.html](index-v2.html)
- [css/styles-v2.css](css/styles-v2.css)
- [pages/crud-eventos.html](pages/crud-eventos.html)
