# Un universo de flores amarillas para Steff

Una galaxia dorada con ramos que giran alrededor de un corazón. Cada ramo abre una carta con su foto.

Es una página estática: un solo `index.html` y una carpeta `images/`. No necesita instalar nada.

## Ver la página

Abre `index.html` en el navegador, o publícala con GitHub Pages (Settings → Pages → Deploy from a branch → `main` / `/ (root)`).

## Cambiar fotos y cartas

Todo se edita al inicio del `<script>` de `index.html`, en la lista `RAMOS`:

- `foto`: ruta de la foto de esa carta (por ejemplo `images/ascensor.jpg`).
- `posicion`: encuadre de la foto dentro del recuadro (`"center 30%"`). Sube el segundo número para ver más de la parte baja de la foto y bájalo para ver más de la parte alta.
- `titulo` y `carta`: el texto de la carta.

Para agregar un ramo, copia un bloque de `RAMOS` y cambia sus datos. Los ramos se reacomodan solos.

## Fotos

| Carta | Archivo |
| --- | --- |
| Te amo (y corazón central) | `images/atardecer-capuchas.jpg` |
| Eres mi sol | `images/cielo-azul.jpg` |
| Mi amor | `images/beso-peluche.jpg` |
| Eres preciosa | `images/cardigan-amarillo.jpg` |
| Siempre juntos | `images/ascensor.jpg` |
| Eres mi todo | `images/selfie-divertida.jpg` |
| Mi vida entera | `images/tienda-espejo.jpg` |
| Mi lugar favorito | `images/abrazo-cama.jpg` |
