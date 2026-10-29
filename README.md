# Naciones

Proyecto personal de juego idle/estrategia ambientado en la Luna. Dos etapas del mismo proyecto, en este repo:

## `prototipo-v1/` — primer prototipo jugable

Un único archivo HTML/CSS/JS, sin backend, para iterar rápido sobre las mecánicas centrales: esquema de biomas (montaña, llanura, selva, desierto) con producción, terreno y fortalezas/debilidades propias de cada uno. El balance de biomas se ajustó simulando miles de partidas hasta encontrar una distribución pareja de resultados entre los cuatro tipos.

## `public/` — segunda iteración, con backend real

Reescritura sobre **Firebase** (Auth + Firestore) para soportar partidas persistentes multi-sesión: login, estado de partida en la nube, sincronización en tiempo real. Incluye intro animada y assets propios.

## Stack

HTML/CSS/JavaScript vanilla · Firebase (Auth, Firestore, Hosting)

## Estado

En diseño y prototipado — no es un juego terminado ni publicado.
