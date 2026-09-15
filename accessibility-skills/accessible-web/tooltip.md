---
id: accessibility-skills-web-tooltip
title: "Tooltip"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/tooltip/
---

[Source material](https://www.atomica11y.com/accessible-web/tooltip/)

# Web Tooltip skills



## How to test a tooltip 

Given that I am on a screen with a tooltip

### 1. Keyboard only

- WHEN I use the arrow keys or tab key

  - I SEE nothing, because we don't use tooltips


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow keys or tab key

  - I HEAR nothing, because we don&#39;t use tooltips


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe

  - I HEAR nothing, because we don&#39;t use tooltips


A tooltip must meet WCAG principles:

### 1. Perceivable

- Nothing to perceive because we don't use tooltips

### 2. Operable

- No need to operate because we don't use tooltips

### 3. Understandable

- The rest of the UI is understandable so we don't need tooltips to explain it

### 4. Robust

- The design is super robust because it doesn't rely on tooltips

## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Tooltip

Tooltip usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Do not use tooltips. Put in the work to design and edit the UI language so that it is self-explanatory on the first pass.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a tooltip more effectively.

- Do not hide critical instructions or error messages inside hover-activated tooltips.


### Tooltip misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a tooltip. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Tooltips indicate poor UX design and hide necessary context; if information is important, it should be visible by default.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15