---
id: atomica11y-skills-web-popover
title: "Popover"
description: Code and test accessible Web Popover. Use when a control reveals non-modal contextual content while the underlying content remains available.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/popover/
---

[Source material](https://www.atomica11y.com/accessible-web/popover/)

# Web Popover skills



## How to test a popover 

Given that I am on a screen with a popover

### 1. Keyboard only

- WHEN I use the tab key to move focus to a popover button

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar and/or enter key to activate a popover button
 
  - I SEE the popover surface expands/collapses

- THEN when I use the tab key to move focus to a control in the popover
 
  - I SEE each option is focused

- OR when I use the tab key to move focus out of the popover
 
  - I SEE focus leaves the popover, I am not trapped in the popover


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a popover button

  - I HEAR its purpose is clear

  - I HEAR the popover button identifies its role as button

  - I HEAR popover button expresses its state (expanded/collapsed)

- THEN when I use the spacebar and/or enter key to activate a popover button
 
  - I HEAR the popover surface expands/collapses

- THEN when I use the tab key to move focus to a control in the popover
 
  - I HEAR each option is focused

- OR when I use the tab key to move focus out of the popover
 
  - I HEAR focus leaves the popover, i am not trapped in the popover


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a popover button

  - I HEAR its purpose is clear

  - I HEAR the popover button identifies its role as button

  - I HEAR popover button expresses its state (expanded/collapsed)

- THEN when I doubletap with the button in focus
 
  - I HEAR the popover expands/collapses


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Popover

Popover usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use popovers to allow a small piece of content to pop over existing content.
- Use popovers as a lightweight component that should not contain heavy content or important alerts like modal dialogs do.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a popover more effectively.

- Do not use popovers that trap focus.


### Popover misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a popover. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Popovers and dialog modals do not follow the same accessibility rules.
- Popovers are not tooltips.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17