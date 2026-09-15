---
id: atomica11y-skills-web-table
title: "Table"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/table/
---

[Source material](https://www.atomica11y.com/accessible-web/table/)

# Web Table skills



## How to test a table 

Given that I am on a screen with a table

### 1. Keyboard only

- WHEN I use the arrow keys

  - I SEE the table scrolls into view (but is not focusable)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow keys

  - I HEAR the table has a caption or a heading to describe its purpose

  - I HEAR it identifies itself as a table

  - I HEAR if sorted dynamically, sort order is identified (up/down, ascending/descending)

  - I HEAR column headers and row headers are identified with screenreader shortcuts


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focusable elements in the footer

  - I HEAR the table has a caption or a heading to describe its purpose

  - I HEAR it identifies itself as a table

  - I HEAR if sorted dynamically, sort order is identified (up/down, ascending/descending)

  - I HEAR column headers and row headers are identified with screenreader shortcuts


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Table

Table usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use tables strictly for tabular data, not for visual layout.
- Always include a caption and identify row and column headers to provide context for screen reader users.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a table more effectively.

- Do not use empty header cells for visual spacing.
- Do not omit the <code class="language-plaintext highlighter-rouge">&lt;th&gt;</code> and <code class="language-plaintext highlighter-rouge">scope</code> attributes, as they are required to map data cells to their headers.
- Do not use clickable cells to sort or reveal content. Insert a clear control like a button.


### Table misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a table. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Tables are not the only way to display structured data. Unordered lists, ordered lists or definition lists can also describe structured information.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15