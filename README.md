# K Cube

Animated line-drawn K mark for Kyle Covey ([KyleCovey.com](https://kylecovey.com)).

![K Cube](k-cube-black.svg)

## Files

| File | What it is |
| --- | --- |
| `k-cube-black.svg` | Square version on black with breathing room. Good for avatars, social, and slides. |
| `k-cube.svg` | The mark on its own with a transparent background, tightly cropped. |

## Using it

Both files are self-contained SVGs. The animation runs in pure CSS, with no JavaScript.

```html
<img src="k-cube-black.svg" alt="K" width="240">
```

- **Line color:** the transparent version uses the CSS variable `--kc` (white by default). When the SVG is inlined in a page, set `--kc` on a parent to change the color.
- **Reduced motion:** the animation pauses for visitors who have reduced motion turned on.
- **Speed:** one loop takes 5 seconds (`5.0000s` in the `<style>` block).

## Rights

© Kyle Covey. All rights reserved. This mark is not licensed for reuse.
