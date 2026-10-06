# Tipografía

## La regla de combinación

La frase va en una **sans** y la **palabra con sentido** va en una **serif**. Una sola palabra o remate en serif por frase. Así se ve en todo:

- Video: "**Male** *Gozalo*", "**¿Querés ver** *cómo lo hago?*", "**publicar con** *sentido*".
- Carruseles: "**Un prompt,** *un resultado.*", "**Mismo negocio.** *Dos formas* **de usar IA.**"

La excepción son las **portadas de reels**: ahí va **solo Poppins**, y la palabra clave en Poppins itálica.

## Las familias

| Familia | Dónde se usa | Archivos en `tipografias/` |
|---|---|---|
| **Poppins** | Todo lo de video: subtítulos, textos animados, pastillas, portadas. | Regular, Medium, SemiBold, SemiBoldItalic, Bold, BoldItalic, ExtraBold |
| **Playfair Display** Bold Italic | La palabra en serif dentro de los videos. | PlayfairDisplay-BoldItalic |
| **Figtree** | Títulos y textos de los carruseles; cuerpo de la app MG Studio. | Regular, Medium, SemiBold, Bold |
| **Instrument Serif** | El remate en serif de los carruseles. | Regular, Italic |
| **Fraunces** | Solo títulos de la app interna MG Studio. | SemiBold, SemiBoldItalic |

Todas son gratis en Google Fonts.

## Medidas en video vertical (1080×1920)

| Elemento | Fuente | Tamaño | Color y detalle |
|---|---|---|---|
| Subtítulo (una palabra) | Poppins Bold 700 | 86 px | `blanco`, palabras clave en `amarillo-logo`. Sombra `0 4px 18px rgba(0,0,0,.55), 0 2px 4px rgba(0,0,0,.45)` |
| Texto gigante, sans | Poppins ExtraBold 800 | 116 px | `blanco`, sombra lila suave |
| Texto gigante, palabra serif | Playfair Display Bold Italic | 250 px | `amarillo-logo` |
| Nombre en pantalla | "Male" Poppins ExtraBold 92 px + "Gozalo" Playfair Bold Italic 96 px | | `tinta` + `indigo` |
| @male.gozalo | Poppins SemiBold | según el espacio | `tinta` sobre una barra tipo marcador `amarillo-logo` |
| Pregunta de cierre | Poppins ExtraBold 76 px + Playfair Bold Italic 92 px | | `tinta` + `indigo` |
| Pastilla | Poppins Bold 700 | 42 px | Relleno 22 × 38 px, bordes redondos completos |

## Medidas en portadas de reels (1080×1920)

| Línea | Fuente | Tamaño | Color |
|---|---|---|---|
| Línea 1 ("Publicá con") | Poppins Bold 700 | 104 px, interletrado −0,02 em | `lila` |
| Línea 2 ("sentido") | Poppins Bold Italic 700 | 116 px, girada −5° | `amarillo-suave` |

## Medidas en YouTube (1920×1080)

| Elemento | Fuente | Tamaño | Color |
|---|---|---|---|
| Subtítulos | Poppins SemiBold 600 | 64 px, margen inferior 110 px | `blanco`, una palabra resaltada por bloque en `yt-beige` |
| Intro | Poppins Bold | | "Male Gozalo · Marketing para Emprendedores" |

## Medidas en carruseles (1080×1350)

Medidas aproximadas, tomadas de los carruseles de octubre de 2026.

| Elemento | Fuente | Tamaño aprox. |
|---|---|---|
| Título | Figtree Medium 500 | 90 px, interlineado 1,1 |
| Remate | Instrument Serif 400 | 104 px, interlineado 1 |
| Cuerpo | Figtree Regular 400 | 30 px, interlineado 1,5 |
| Pastilla | Figtree Bold 700, MAYÚSCULAS | 26 px, interletrado 0,12 em |
| Pie (@male.gozalo y "1 / 8") | Figtree Regular 400 | 22 px |

## App interna MG Studio

Títulos en **Fraunces** 600 (33 px en la cabecera) y textos en **Figtree** 15 px.

## Versiones anteriores

- El carrusel de junio usaba Playfair Display + DM Sans.
- El reel "Miles de views ≠ ventas" (v2, 1 de octubre) usó Fraunces + Figtree.

Quedan como referencia; lo vigente es lo de arriba.
