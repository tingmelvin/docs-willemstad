---
title: 'Using Admonitions Pseudo-Reading-Mode Live Preview Tables for Willemstad X users'
date: 2022-04-24
permalink: /ext/adm/tables
eleventyNavigation:
  key: Extensions
  parent: Home
  order: 531
  title: 'Live Preview Tables'
---
Please follow these instructions:

1. Download the <u>Admonition</u> plugin by Jeremy Valentine on [the Community Plugin store within Obsidian](obsidian://show-plugin?id=obsidian-admonition).
3. In the <u>Admonition</u> plugin options, go to `Add New`, then at the input boxes on `Admonition Type:`, type `table` (the other input boxes are not of importance here)
3. Create an Admonition with
```
`​`​`ad-table
title:
color:

(table code goes here)
`​`​`
``` 
4. Table should render exactly in LP as in Reading mode.

5. If you want to edit said table easily and have Advanced Tables recognise the spaces it needs to add/remove, just type the three backticks below the `color:` and edit and then remove it once you're done editing.
6. Profit! You should have something looking like the following: (L: Reading mode, C: Live Preview, R: Live Preview editing)
![[Pasted image 20220222211348.png]]


---
### Alternatives — 'Live Preview Almost-True Rendering'

Alternatively, if editing easily is of more importance to you, you can opt to use the <u>Live Preview Almost-True Rendering</u> option via `Typography` > `Tables` in the <u>Style Settings</u> plugin. This renders the tables *quite* similar in Live Preview as it is in Reading mode. See below for an example —
![[Pasted image 20220222214717.png]]

---
> <u>Last updated</u> — 2022-02-22 ![](https://img.shields.io/badge/version-0.1.5-00BD6E)