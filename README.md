# Indie Gaia Marp Theme

**Modern CSS features for Yuki Hattori’s [Marp Gaia](https://github.com/marp-team/marp-core/blob/main/themes/gaia.scss) theme.**

## Overview

- System font stack with `system-ui, sans-serif`
- Support for `color-scheme: light dark`
- Support for `prefers-contrast: less|more`
- Typographic blockquotes for `lang="de|en|es|fr|it|CH"`
- Compatible to Gaia’s `invert` and `gaia` coloring.

## Usage

Download [./indie-gaia.css](indie-gaia.css) to your presentation project and add it to your Marp frontmatter. Start Marp’s built-in server with `marp -s .` and visit [http://localhost:8080/](http://localhost:8080/)

```markdown
---
theme: indie-gaia
---
```

>  **VS Code** users will want to read the recipe [The easy way (with VS Code)](https://yoanbernabeu.github.io/MARP-Template-Library/docs/intro/) over on *MARP Template Library.*

## Features

### Color Schemes and Contrast

Colors in this scheme are based on the original [Marp Gaia](https://github.com/marp-team/marp-core/blob/main/themes/gaia.scss) theme. *Indie Gaia* will display the HTML presentation according to the current **light** or **dark color scheme** as defined in browser or OS. 

- Both the  `gaia` and `invert` settings work as expected.
- User settings for `prefers-contrast` are supported.

### Typographic blockquotes

Like in original Gaia theme, blockquotes are enclosed with decorative typographic quotes. *Indie Gaia* chooses the quotation marks according to the presentation language or the blockquote language.

**Default: presentation language** 

```markdown
---
lang: en-GB
---

> Imagine if every Thursday your shoes exploded if you tied them the usual way. This happens to us all the time with computers, and nobody thinks of complaining 
> — Jef Raskin, 1943—2005
```

**Using blockquote language**

```markdown
---
lang: en-US
---

> <span lang="de">Theorie ist, wenn man alles weiß und nichts funktioniert. Praxis ist, wenn alles funktioniert und niemand weiß warum.</span> ...
```

#### Available Languages

| Scope             | lang                        | Font family         |
| ----------------- | --------------------------- | ------------------- |
| Default / English | `en` and `en-*` *or empty*  | **`“`** and **`”`** |
| Germany           | `de` and `de-*`             | **`»`** and **`«`** |
| France            | `fr` and `fr-*`             | **`«`** and **`»`** |
| Italy             | `it` and `it-*`             | **`«`** and **`»`** |
| Spain             | `es` and `es-*`             | **`«`** and **`»`** |
| Switzerland       | `*-CH` — precedes any above | **`«`** and **`»`** |



### No external Webfonts

The original Gaia theme requires webfonts from an external webserver; this practice in some countries is considered a privacy protection problem. *Indie Gaia* instead makes use of generic CSS fonts. 

Every major computer platform nowadays uses excellent and well-made OS fonts, so your presentation should look fine and legible on each. Note, however, that slides may look different on different platforms depending on the flow and amount of text.

| Scope        | Font family                                        |
| ------------ | -------------------------------------------------- |
| Slides       | `system-ui, ui-sans-serif, sans-serif`             |
| Code         | `ui-monospace, (… common mono fonts …), monospace` |
| Block quotes | `ui-serif, (… common serif fonts…), serif`         |



---

## MIT License

See [LICENSE](LICENSE) document.

