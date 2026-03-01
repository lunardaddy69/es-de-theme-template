# Zune HD Theme for ES-DE
### Based on [Art Book Next](https://github.com/anthonycaccese/art-book-next-es-de) by anthonycaccese

A theme for [ES-DE](https://es-de.org/) inspired by the Zune HD software UI — Microsoft's acclaimed media player interface that pioneered what would later become Windows Phone's Metro design language.

---

## Design Language

The Zune HD UI was built on:

- **Near-black backgrounds** — deep charcoal rather than pure black, giving warmth without sacrificing contrast
- **White typography** — clean, unadorned, at varying opacities to create hierarchy
- **Single vivid accent color** — used sparingly on selected items, logos, icons, and highlights
- **Desaturated background artwork** — system art is tinted down so the accent color pops
- **Minimalism** — no gradients, no chrome, content first

---

## Color Schemes

Three Zune HD accent variants are available in the **Theme Color Scheme** menu:

| Scheme | Accent | Notes |
|---|---|---|
| `Zune HD [Orange]` | `#F2740D` | The "Atomic" orange, most iconic Zune color |
| `Zune HD [Magenta]` | `#FF1F5A` | Classic Zune HD hardware/software magenta |
| `Zune HD [Green]` | `#8DC60A` | Zune's signature lime/chartreuse green |

All three use the same base palette:
- Background: `#111111`
- Gamelist panel: `#1C1C1C`
- Primary text: `#FFFFFF` at varying opacity
- Selected item text: `#111111` (dark, readable on the vivid accent background)
- System artwork: desaturated to ~50% to let the accent color dominate

---

## Installation

1. Clone or download this repository into your ES-DE themes folder:
   ```
   /ES-DE/themes/es-de-theme-template/
   ```
2. Launch ES-DE and go to **UI Settings → Theme**
3. Select this theme, then under **Theme Color Scheme** choose one of the `Zune HD` options

---

## Font Notes

The Zune HD software used Microsoft's **Segoe WP** font family. To get closer to the authentic look:

1. Download **Nunito** (free, Google Fonts) — the closest open-source match in weight and feel
2. Place `Nunito-Light.ttf` and `Nunito-Medium.ttf` in `./_inc/fonts/`
3. Update the font variables in `theme.xml`:
   ```xml
   <fontLight>./_inc/fonts/Nunito-Light.ttf</fontLight>
   <fontRegular>./_inc/fonts/Nunito-Medium.ttf</fontRegular>
   ```

---

## Recommended Variant

For the most authentic Zune pivot-style experience, use:

**`List: Metadata & Boxart`** or **`List: Metadata & Screenshot + Marquee`**

These variants put the game list on the left ~37% of the screen with artwork filling the right side — closely matching the Zune HD's content-heavy layout.

---

## Credits

- Original theme: [Art Book Next](https://github.com/anthonycaccese/art-book-next-es-de) by [anthonycaccese](https://github.com/anthonycaccese)
- System logos: [Dan Patrick](https://archive.org/details/console-logos-professionally-redrawn-plus-official-versions)
- Metadata icons: [Phosphor Icons](https://phosphoricons.com/)
- Zune HD design language inspiration: Microsoft (2009)

## License

Creative Commons CC-BY-NC-SA — https://creativecommons.org/licenses/by-nc-sa/2.0/

You are free to share and adapt this theme as long as you provide attribution back to anthonycaccese (and the above credits) and share any updates under the same licence terms.
