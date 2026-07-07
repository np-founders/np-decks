# np-decks

Hosting público (GitHub Pages) de las presentaciones comerciales **nuevas** de nullplatform.

Live base: `https://np-founders.github.io/np-decks/`

- La **raíz** es una landing neutra a propósito (no lista ni enlaza los decks).
- Cada presentación vive en su propio path **no adivinable**, ej: `/np-decks/gv-deck-xxxxxxxx/`.
- Este repo es solo **destino de deploy** — NO se edita a mano.

## Publicar

Las presentaciones se generan y mantienen en el repo privado `presentaciones-comerciales`
y se publican con su script:

```bash
# desde presentaciones-comerciales/
./scripts/publish.sh decks/<deck> <slug>
```

El slug define la URL final: `https://np-founders.github.io/np-decks/<slug>/`.

> `public-mvs-deck` quedó como **legacy** (solo el deck principal en su raíz, con la URL
> ya distribuida). Las presentaciones nuevas van todas acá.
