---
id: atomica11y-skills-web-expander
title: "Expander accordion"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/expander/
---

[Source material](https://www.atomica11y.com/accessible-web/expander/)

# Web Expander accordion skills



## How to test an expander accordion 

Given that I am on a screen with an expander accordion

### 1. Keyboard only

- WHEN I use the tab key to move focus to an expander

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar and/or enter key to activate the expander
 
  - I SEE the hidden content is revealed


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to an expander

  - I HEAR its purpose is clear

  - I HEAR it identifies its role of button or summary

  - I HEAR it expresses its state (expanded/collapsed)

- THEN when I use the spacebar and/or enter key to activate the expander
 
  - I HEAR the hidden content is revealed


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a button

  - I HEAR its purpose is clear

  - I HEAR it identifies its role of button or summary

  - I HEAR it expresses its state (expanded/collapsed)

- THEN when I doubletap with the button in focus
 
  - I HEAR the intended action occurs


### 4. Device settings

- WHEN I use custom font settings I SEE text resizes up to 200% without losing information

- WHEN I use magnification or pinch-to-zoom I SEE expand/collapse indicator is in visual proximity to text label


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Expander accordion

Expander accordion usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use expanders to conceal accessory content.
- Because expanders hide content by default, they should be used sparingly, if at all.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a expander accordion more effectively.

- Do not make the entire content of the expander focusable. Only the summary control should be focusable.
- Do not place mission critical information inside an expander.
- Do not use expanders for navigation items. Use a popover instead.
- Do not use expanders to trigger content appearing elsewhere on screen.


### Expander accordion misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a expander accordion. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- An expander should not automatically collapse when another one opens.
- Pages with a lot of content are not improved by placing content in expanders to make the page shorter. People do know how to scroll, but they may miss content when it’s collapsed.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16