# Borozdov Specimen

A theme from the Borozdov collection. Two faces — light **Proof**, a type specimen museum on
white paper, and dark **Matrix**, the same specimens cast in reverse. A giant deco display
face, square hairline boxes, tracked small labels and no colour at all.

![Borozdov Specimen in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/specimen/main/screenshots/light.png)

![Borozdov Specimen in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/specimen/main/screenshots/dark.png)

## Principles

- **The type is the exhibit.** Poiret One, a thin deco display face, sets the title at
  specimen size and the three largest headings, never bold; pull quotes are set in it too.
- **One white, one black.** No colour anywhere: inversion marks the highlighter, the main
  button and the open file.
- **Hairlines and square corners.** Every callout, code block, table, tag and field is a
  square box drawn by a 1px line; trouble gets a heavier rule; no shadows, even on floating
  panels.
- **Museum labels.** Callout titles, table headers, tags and property names are small
  capitals tracked open.

## Features

- Light and dark modes, following Settings → Appearance → Base color scheme
- The title at specimen size in a deco display face
- An inverted highlighter, main button and open file instead of an accent colour
- Callouts as hairline boxes with tracked capital labels; trouble gets a heavier rule
- Pull quotes in the display face, a size and a half up
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Utility**. Install Borozdov Utility under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Specimen** under Style Settings → Borozdov Utility → Variant. The variant brings
this theme's palette, type and corners; its own layout, and its embedded font if it has
one, come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the [latest
release](https://github.com/borozdov-obsidian-themes/specimen/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Specimen/`, then choose Borozdov Specimen under Settings
→ Appearance → Themes.

## Font

Poiret One (© 2011 Denis Masharov) is embedded in `theme.css` as base64 WOFF2 under the SIL
Open Font License 1.1 — see [`fonts/OFL.txt`](fonts/OFL.txt). One weight, Latin and
Cyrillic, for the title, the three largest headings and pull quotes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: светлый «Оттиск» — музей шрифтовых
образцов на белой бумаге, и тёмный «Матрица» — те же образцы, отлитые в негативе. Огромный
акцидентный заголовок (Poiret One), квадратные рамки в волосяную линию, мелкие подписи
вразрядку и никакого цвета: выделение, главная кнопка и открытый файл отмечены инверсией.
В каталоге тема живёт вариантом Borozdov Utility: установите Borozdov Utility и плагин Style Settings, затем выберите Specimen в Style Settings → Borozdov Utility → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
