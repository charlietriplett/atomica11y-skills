---
id: accessibility-skills-web-iframe
title: "iframe"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/iframe/
---

# Web iframe skills



## How to test an iframe 

Given that I am on a screen with an iframe

### 1. Keyboard only

- WHEN I use the arrow keys or tab key

  - I SEE the content of the iframe is browsed


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow keys or tab key

  - I HEAR the title of the iframe is read if the iframe contains content 

  - I HEAR if the iframe does not contain content, the iframe is ignored


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to content in the iframe

  - I HEAR the title of the iframe is read if the iframe contains content 

  - I HEAR if the iframe does not contain content, the iframe is ignored


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a iframe

iframe usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use an iframe to embed third-party or isolated content.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a iframe more effectively.

- Do not use empty, missing, or generic title attributes on functional embeds.


### iframe misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a iframe. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Empty iframes are not transparent to screen readers. An iframe must have a title to be valid html and use aria-hidden=”true” to hide it from screen readers.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13