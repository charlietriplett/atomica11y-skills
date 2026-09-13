---
id: accessibility-skills-web-tabs
title: "Tab group"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/tabs/
---

[Source material](https://www.atomica11y.com/accessible-web/tabs/)

# Web Tab group skills



## How to test a tab group 

Given that I am on a screen with a tab group

### 1. Keyboard only

- WHEN I use the tab key to move focus to a tab

  - I SEE focus is strongly visually indicated on the activated tab

- IF TAB ACTIVATION IS MANUAL when I use the left/right arrow keys
 
  - I SEE focus moves to other tabs and I use the spacebar or enter key to activate the tab

- IF TAB ACTIVATION IS AUTOMATIC when I use the left/right arrow keys
 
  - I SEE the tab is activated

- THEN when I use the tab key
 
  - I SEE focus moves to the activated tab panel


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a tab

  - I HEAR its label and purpose is clear

  - I HEAR it identifies itself as a tab

  - I HEAR it expresses its state (selected/pressed/checked)

- IF TAB ACTIVATION IS MANUAL when I use the left/right arrow keys
 
  - I HEAR focus moves to other tabs and i use the spacebar or enter key to activate the tab

- IF TAB ACTIVATION IS AUTOMATIC when I use the left/right arrow keys
 
  - I HEAR the tab is activated

- THEN when I use the tab key
 
  - I HEAR focus moves to the activated tab panel


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a tab

  - I HEAR its label and purpose is clear

  - I HEAR it identifies itself as a tab

  - I HEAR it expresses its state (selected/pressed/checked)

- THEN when I doubletap with the tab in focus
 
  - I HEAR the state is changed


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Tab group

Tab group usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use tabs when conent changes but the URL does not change during the interaction.
- Use tabs when switching between related sections of content within the same page.
- Use tabs when the sections are peer-level and mutually exclusive (only one visible at a time).
- Use tabs when content density requires progressive reveal without navigation.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a tab group more effectively.

- Do not use tabs for primary site navigation; use navigation and links instead.
- Do not make tabs change location or route; that is navigation.


### Tab group misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a tab group. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Tabs are not navigation just because they look like it.
- Navigation links are not tabs just because they look like it.
- Tabs do not make information easier to find by making the page shorter; they decrease discoverability by adding required interaction friction.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13