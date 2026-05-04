# reign-fonts

The type system behind [Reign](https://christaphur.com) 
"a design and consulting practice at the intersection of operations and branding."

This is an open library. If it helps you innovate, use it.

---

## Fonts

| Variable | Family | Role |
|---|---|---|
| `--font-display` | Bebas Neue | Display, headers, numerals |
| `--font-serif` | DM Serif Display | Editorial, pull quotes |
| `--font-mono-identity` | IBM Plex Mono | Labels, eyebrows, identity |
| `--font-mono-utility` | DM Mono | Tags, metadata, data |
| `--font-body` | DM Sans | Body text, UI, captions |

All fonts served via Google Fonts.

---

## Usage

**Option 1 — Link the file directly**

Download `reign-fonts.css` and link it in your HTML:

```html
<link rel="stylesheet" href="reign-fonts.css">
```

**Option 2 — Copy the import**

Paste the Google Fonts import into your own CSS:

```css
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Mono:wght@400;500&family=DM+Sans:wght@400;500;700&family=DM+Serif+Display&family=IBM+Plex+Mono:wght@400;500&display=swap');
```

**Then reference fonts via CSS variables:**

```css
h1 { font-family: var(--font-display); }
h2 { font-family: var(--font-serif); }
p  { font-family: var(--font-body); }

/* Labels / eyebrows */
.label { font-family: var(--font-mono-identity); }

/* Tags / metadata */
.tag { font-family: var(--font-mono-utility); }
```

---

## Color System

The Reign color system pairs with this type system. Hex values for reference:

| Name | Hex |
|---|---|
| Black | `#0A0A0A` |
| Cream | `#F0E8B5` (approx) |
| Gold | `#C9A84C` |
| Dim | `#B87B2E` (approx) |
| Muted | `#C0C779` (approx) |

---

## About

Reign is a solo consulting practice founded by Christopher Nwalupue, focused on business operations and brand systems.

[christaphur.com](https://christaphur.com) · [@christaphur](https://instagram.com/christaphur)
