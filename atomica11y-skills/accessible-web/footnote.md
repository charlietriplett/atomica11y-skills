---
id: atomica11y-skills-web-footnote
title: "Footnote"
description: Code and test accessible Web Footnote. Use when supplementary Web content is referenced from the main text.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/footnote/
---

[Source material](https://www.atomica11y.com/accessible-web/footnote/)

# Web Footnote skills



## How to test a footnote 

Given that I am on a screen with a footnote

### 1. Keyboard only

- WHEN I use the tab key to move focus to a footnote link

  - I SEE focus is strongly visually indicated

- THEN when I use the enter key to activate the link
 
  - I SEE my focus moves directly to the targeted footnote


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a footnote link

  - I HEAR it describes its purpose

  - I HEAR it identifies itself as a link

- THEN when I use the enter key to activate the link
 
  - I HEAR my focus moves directly to the targeted footnote


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a footnote link

  - I HEAR it describes its purpose

  - I HEAR it identifies itself as a link

- THEN when I doubletap with the link in focus
 
  - I HEAR my focus moves directly to the targeted footnote


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Footnote

Footnote usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use footnotes to allow people to reference more detailed information about a term or definition.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a footnote more effectively.

- Do not use footnotes that strand keyboard users at the bottom of the page without a return mechanism.


### Footnote misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a footnote. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Footnote links do not require additional minimum clickable area as the default size defined by the user agent is considered adequate.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16