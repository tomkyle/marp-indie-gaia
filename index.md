---
theme: indie-gaia
lang: en-US
---



<!-- 
_class: lead
-->

# Indie Gaia
Opinionated Marp Theme
Inspired by and based on 
Yuki Hattori’s classic [Gaia](https://github.com/marp-team/marp-core/tree/main/themes#gaia) theme

---


<!-- 
_class: lead
-->

## Features 

- System font stack with `system-ui, sans-serif`
- Support for `color-scheme: light dark`
- Support for `prefers-contrast: less|more`
- Typographic blockquotes for `lang="de|en|es|fr|it|CH"`
- Compatible to Gaia’s `invert` and `gaia` coloring

---

<!-- 
_class: invert 
-->

# Inverted colors

Swap background and foreground color,  
as created by [marp-team](https://github.com/marp-team/)

Frontmatter: `_class: invert`

![bg right 50%](https://github.com/marp-team.png)


---

<!-- 
_class: gaia 
-->


# Accentuated slides

The Gaia scheme for accentuated slides,  
as created by [marp-team](https://github.com/marp-team/)

Frontmatter: `_class: gaia`


---

<!-- 
_class: lead
-->

## Typographic Blockquotes

Adapt to presentation language
Adjustable by blockquote language



---

<!--
_footer: Typographic Blockquotes
-->

## Adaptive Quotation Marks

Quotation marks adapt to presentation language.

> Imagine if every Thursday your shoes exploded if you tied them the usual way. This happens to us all the time with computers, and nobody thinks of complaining — Jef Raskin, 1943—2005


```markdown
---
lang: en-GB
---

> Imagine if every Thursday your shoes exploded ...
```


---


## Adaptive Quotation Marks

<!--
_footer: Typographic Blockquotes
-->

Blockquote language changes quotation marks:

`<span lang="de|en|es|fr|it|CH">`

```markdown
---
lang: en-US
---

> <span lang="de"> ... </span> ...
```

---

<!--
_footer: Typographic Blockquotes
-->

## German Guillemets

> <span lang="de">Theorie ist, wenn man alles weiß und nichts funktioniert. Praxis ist, wenn alles funktioniert und niemand weiß warum.</span>


```markdown
> <span lang="de">Theorie ist, wenn man alles weiß ... </span>
```


---


<!--
_footer: Typographic Blockquotes
-->
## French Guillemets


> <span lang="fr">L’ordinateur est un truc qui sert à résoudre des problèmes qu’on n’aurait pas si on n’avait pas d’ordinateur.</span>


```markdown
> <span lang="fr"> L’ordinateur est un truc ... </span>
```



---


## Table example

| Name    | Age | City    | Salary |
|---------|----:|---------|-------:|
| Alice   | 25  | Berlin  | 25,000 |
| Bob     | 30  | Munich  | 30,000 |
| Charlie | 35  | Hamburg | 35,000 |



---

<!-- 
_class: invert
-->

## Table example · inverted


| Name    | Age | City    | Salary |
|---------|----:|---------|-------:|
| Alice   | 25  | Berlin  | 25,000 |
| Bob     | 30  | Munich  | 30,000 |
| Charlie | 35  | Hamburg | 35,000 |

Frontmatter: `_class: invert`

---

<!-- 
_class: gaia 
-->

## Table example · accentuated


| Name    | Age | City    | Salary |
|---------|----:|---------|-------:|
| Alice   | 25  | Berlin  | 25,000 |
| Bob     | 30  | Munich  | 30,000 |
| Charlie | 35  | Hamburg | 35,000 |

Frontmatter: `_class: gaia`



---


## Source Code

Inline `source code` and code block:

```javascript
{ foo: "bar" }
```


---

<!-- _class: invert -->
## Source Code · inverted

Inline `source code` and code block:

```javascript
{ foo: "bar" }
```

Frontmatter: `_class: invert`


---

<!-- _class: gaia -->
## Source Code · accentuated

Inline `source code` and code block:

```javascript
{ foo: "bar" }
```


Frontmatter: `_class: gaia`


