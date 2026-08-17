# Línea de tiempo de Lizbeth Gárate

Dos versiones de la misma historia (2011 → hoy), con las mismas fotos y textos:

- `index.html` — recorrido vertical, etapa por etapa.
- `3d.html` — túnel de recuerdos en 3D: la cámara avanza en profundidad con el scroll.

Cada página tiene un botón discreto abajo para saltar a la otra.

**Todo va incrustado dentro de cada archivo** (fotos, tipografías, audio). Son autocontenidos:
funcionan abriéndolos desde el celular o la computadora, incluso sin internet.

## Publicar en GitHub Pages

1. Sube `index.html` y `3d.html` a la raíz del repositorio `carmont52/Lizbeth`
   (Add file → Upload files → arrastra los dos → Commit).
2. **Settings → Pages → Source: Deploy from a branch → main / (root)** → Save.
3. En ~1 minuto queda en `https://carmont52.github.io/Lizbeth/`

> El repositorio es privado y GitHub Pages en repos privados requiere plan pago.
> Para un link abierto: **Settings → General → Change visibility → Public**.
> Alternativa sin GitHub: mandarle el archivo por WhatsApp o correo — se abre igual.

### Si el deployment falla

Un error `429 (Too Many Requests)` al descargar `jekyll-build-pages` es una falla temporal de
GitHub, no de estos archivos: ve a **Actions** → la ejecución fallida → **Re-run all jobs**.

El archivo `.nojekyll` (vacío, incluido aquí) le dice a Pages que publique el HTML tal cual sin
pasarlo por Jekyll. Súbelo también a la raíz.

## Audio

El botón *Poner música* (arriba a la derecha) inicia el ambiente; no arranca solo porque los
navegadores bloquean el audio automático. Se genera con Web Audio —notas de celesta en escala
pentatónica— así que no hay canciones con derechos de autor.

## Etapas

| Fecha | Etapa |
| --- | --- |
| 2011–2013 | Novios |
| Oct 2013 | Matrimonio |
| 2013–2016 | Viajes y primer embarazo |
| May 2016 | Nace Amelia |
| 2016–2020 | Familia y pandemia |
| Ene 2021 | Nace Valentina |
| 2021–hoy | Nosotros cuatro |
| — | La carta |
