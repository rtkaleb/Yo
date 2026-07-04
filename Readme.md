# Clon de Pinterest - Ejercicio

Ejercicio de práctica de HTML: maqueta de una interfaz estilo Pinterest ("Pinterest 2.0"), con secciones aportadas por distintos integrantes de un equipo (identificadas por comentarios de nombre en el código: SCAR, KALEB, JUSEF, TONY NAPOLES, JONATAN, JORG ADAN).

## Tech stack

- HTML5 puro (sin CSS ni JS)

## Contenido

`index.html` incluye:

- Nav lateral izquierdo con iconos (Inicio, Explorar, Crear, Actualizaciones, Mensajes)
- Barra de búsqueda y categorías
- Nav lateral derecho con datos de perfil y cuenta
- Feed principal con artículos de ejemplo (imágenes placeholder)
- Selector de preguntas frecuentes
- Footer con enlaces de la compañía

## Cómo verlo localmente

No requiere instalación ni build.

```bash
open index.html
```

## Problema conocido

`index.html` tiene todo el documento **duplicado**: el `<body>` completo aparece dos veces seguidas (líneas 1–147 y 148–295), aparentemente por un conflicto de merge mal resuelto. Solo se necesita una copia; conviene eliminar la segunda.

Este proyecto es prácticamente idéntico a los repositorios [Trabajo-con-Git](https://github.com/rtkaleb/Trabajo-con-Git) y [PracticaCSS](https://github.com/rtkaleb/PracticaCSS), que contienen la misma maqueta de Pinterest como parte del mismo ejercicio de clase.

## Autor

**Kaleb Torres** (y equipo)
