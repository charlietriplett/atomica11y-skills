---
id: accessibility-skills-web-figure
title: "Maps, charts & graphics"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/figure/
---

# Web Maps, charts &amp; graphics skills



## How to test a maps, charts &amp; graphics 

Given that I am on a screen with a maps, charts &amp; graphics

### 1. Keyboard only

- WHEN I use the arrow key to browse to a figure

  - I SEE the figure comes into view

- THEN when I use the tab key to move focus to figure controls (toggle, show/hide, etc) 
 
  - I SEE the control is in focus

- THEN when I use the spacebar or enter key
 
  - I SEE the intended action occurs


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow key to browse to a figure

  - I HEAR content is described by a heading, alt text or named on focus

  - I HEAR it identifies as a common html element (image, list, table)

  - I HEAR an alternative method of consumption or interaction is available

- THEN when I use the tab key to move focus to figure controls (toggle, show/hide, etc) 
 
  - I HEAR the control is in focus

- THEN when I use the spacebar or enter key
 
  - I HEAR the intended action occurs


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse to an image

  - I HEAR content is described by a heading, alt text or named on focus

  - I HEAR it identifies as a common html element (image, list, table)

  - I HEAR an alternative method of consumption or interaction is available


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Maps, charts & graphics

Maps, charts & graphics usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use charts and maps to convey complex data visually.
- Always provide an alternative, semantic way to consume the visual data, such as a table, list, search function or filter.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a maps, charts & graphics more effectively.

- Do not rely solely on color to distinguish data points. Use patterns, textures, or text labels for people who are color blind.
- Do not embed a chart as a flat image without providing a data equivalent for assistive technologies.


### Maps, charts & graphics misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a maps, charts & graphics. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Complex visual data is not impossible to make accessible. It can almost always be made searchable, filterable or become a table.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13