# Guion del video — TokenGen, 90 segundos

Sin voz en off. Capturas de pantalla con subtítulos en inglés sobreimpresos.
Sin voz evita regrabarlo por acento, pronunciación o ruido, y funciona en LinkedIn
y en un mail donde el tipo lo mira con el sonido apagado.

Grabá a 1920×1080, ventana maximizada, escritorio limpio (sin barra de tareas con
WhatsApp abierto, sin notificaciones). OBS Studio o la grabadora de Windows sirven.

---

## Plano 1 — El problema (0:00 – 0:12)

Pantalla partida o dos planos seguidos: Illustrator con el arte vectorizado a la
izquierda, Fusion 360 con el árbol de operaciones a la derecha, scrolleando el
historial de extrusiones capa por capa.

> Subtítulo: `One custom keychain. About an hour of manual CAD.`

El objetivo de estos 12 segundos es que el que mira reconozca su propio dolor.
Si no tenés el archivo de Fusion a mano, alcanza con mostrar el árbol de
operaciones de cualquier pieza vieja con muchas extrusiones.

---

## Plano 2 — Arrastrar la imagen (0:12 – 0:25)

TokenGen abierto y vacío. Arrastrás el JPG a la ventana, le ponés nombre, creás.
Aparecen las capas de color detectadas solas y la pieza en el visor 3D.

> Subtítulo: `Drop the artwork. Colours are separated automatically.`

No cortes acá: que se vea que el 3D aparece solo, sin apretar nada más. Ese es
el momento en que el pipeline se entiende sin explicación.

---

## Plano 3 — Ajustar en vivo (0:25 – 0:45)

Tres acciones, en este orden:
1. Arrastrar una fila de color para reordenarla → la pieza cambia en el visor.
2. Cambiar la altura de una capa de `0.4` a `0.8` → el relieve sube.
3. Cambiar el filamento de una capa con el cuadradito de color.

> Subtítulo: `Reorder, set relief height, reassign filament. Live.`

Movete despacio. La tentación es ir rápido porque vos ya sabés dónde está todo;
el que mira, no.

---

## Plano 4 — La validación (0:45 – 1:00)

Provocá un error a propósito: dejá la capa de abajo en altura `0` con fondo
propio, o subí las alturas hasta pasarte del tope de relieve. Que aparezca el
aviso sobre el visor. Después arreglalo y mostrá que el aviso desaparece.

> Subtítulo: `It catches what would fail on the printer — before you print it.`

Este plano es el más importante de todos y el que nadie más tiene. Cualquiera
puede generar geometría; lo que vendés es que la geometría sea imprimible.
Si podés, sumá dos segundos de la vista 2D con el detalle fino marcado en rojo.

---

## Plano 5 — Exportar y abrir en el slicer (1:00 – 1:20)

Clic en Exportar. Corte. Bambu Studio abriendo el `.3mf`: se ve la pieza entera,
el árbol con las partes separadas, y los filamentos del proyecto.

> Subtítulo: `Multi-part 3MF. Each colour is already its own part.`

---

## Plano 6 — La pieza real (1:20 – 1:30)

El llavero impreso, en la mano, girándolo despacio bajo luz lateral para que se
vea el relieve. Fondo liso y oscuro.

> Subtítulo: `Same file, printed.`

Cierre con placa fija: tu nombre, el mail y la URL de la página.

---

## Lo que NO va en el video

- Terminal, comandos, `pip install`, código fuente. Al cliente le importa el
  resultado; el stack ya está en la página para el que quiera leerlo.
- Música con letra.
- Más de 90 segundos. Si te pasás, se corta el plano 1, no los planos 4 y 5.

## Cómo publicarlo

Subilo a YouTube como **no listado** y embebelo en la página, o convertilo a MP4
optimizado y ponelo directo con `<video muted loop playsinline>` si pesa menos de
5 MB. La segunda opción es mejor: arranca solo y no le muestra al prospecto un
logo de YouTube con videos sugeridos al final.
