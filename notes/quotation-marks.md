---
title: Quotation marks in different countries
emoji: π£
created: 2020-10-08T16:37:57.000Z
modified: 2020-10-08T16:37:57.000Z
---

- Albanian: `Β«β¦Β»` `βΉβ¦βΊ`
- English: `ββ¦β` `ββ¦β`
- Arab: `Β«β¦Β»` `βΉβ¦βΊ`
- African: `ββ¦β` `ββ¦β`
- Belorussian: `Β«β¦Β»` `ββ¦β`
- Bulgarian: `ββ¦β` `ββ¦β`
- Hungarian: `ββ¦β`
- Greek: `Β«β¦Β»` `βΉβ¦βΊ`
- Danish: `Β»β¦Β«` `βΊβ¦βΉ`
- Hebrew: `Β«β¦Β»` / `'β¦'` `'β¦'` / `<<β¦>>`
- Irish: `ββ¦β` `ββ¦β`
- Icelandic: `ββ¦β` `ββ¦β`
- Spanish: `Β«β¦Β»` `ββ¦β`
- Italian: `Β«β¦Β»`
- Chinese: `ββ¦β` `ββ¦β`
- Latvian: `ββ¦β` `ββ¦β`
- Lithuanian: `ββ¦β` `ββ¦β`
- Dutch: `ββ¦β` `ββ¦β`
- German: `ββ¦β` `ββ¦β`
- Norwegian: `Β«β¦Β»`
- Polish: `ββ¦β` `Β«β¦Β»`
- Portuguese: `ββ¦β` `ββ¦β`
- Romanian: `ββ¦β` `Β«β¦Β»`
- Russian: `Β«β¦Β»` `ββ¦β`
- Serbian: `ββ¦β` `ββ¦β`
- Slovak: `ββ¦β` `ββ¦β`
- Slovenian: `ββ¦β` `ββ¦β`
- Turkish: `ββ¦β` `ββ¦β`
- Ukrainian: `Β«β¦Β»` `ββ¦β`
- Finnish: `ββ¦β` `ββ¦β`
- French: `Β« β¦` `Β» βΉ β¦ βΊ`
- Croatian: `Β»β¦Β«` `βΊβ¦βΉ`
- Czech: `ββ¦β` `ββ¦β`
- Swedish: `ββ¦β` `ββ¦β`
- Estonian: `ββ¦β` `ββ¦β`
- Japanese: `γβ¦γ` `γβ¦γ`

## Different kinds

- `β β`: English double
- `β β`: English Single
- `Β« Β»`: French Β«Christmas treesΒ»
- `β β`: German βpawsβ
- `β β`: Polish
- `Β» Β«`: Swedish reverse
- `" "`: Double universal

## Example CSS

```css
blockquote {
  background: #f9f9f9;
  border-left: 10px solid #ccc;
  margin: 1.5em 10px;
  padding: 0.5em 10px;
  quotes: 'β' 'β' 'β' 'β';
}
blockquote::before {
  color: #ccc;
  content: open-quote;
  font-size: 4em;
  line-height: 0.1em;
  margin-right: 0.25em;
  vertical-align: -0.4em;
}
blockquote p {
  display: inline;
}
```
