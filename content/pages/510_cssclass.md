---
title: 'CSS Classes'
date: 2022-04-24
permalink: /ext/css/
eleventyNavigation:
  key: CSSClass
  parent: Extensions
  order: 510
  title: 'CSS Classes'
---

CSS Classes are one of the ways Obsidian allows us to style our notes differently than the usual theme we are using.

## To use
To use CSS Classes, the `cssClass` key is added to the YAML frontmatter at the top of your note.

An example of how it would be written is:
```
---
cssClass: writing
---
```

Interestingly, Obsidian also allows for multiple CSS Classes to be used in the _same_ document. To do so, simply delineate them with a comma:
```
---
cssClass: writing, latex
---
```

Or list them:
```
---
cssClass: 
- writing
- latex
---
```

---

## Types
*Willemstad* currently offers the following CSS Classes out of the box:

| Class   | Description                                               |     |
| ------- | --------------------------------------------------------- | --- |
| latex   | Formats your document similar to those processed by LaTeX |     |
| writing | Applies an alternate note styling for writers             |     |
|         |                                                           |     |