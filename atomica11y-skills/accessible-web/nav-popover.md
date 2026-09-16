---
id: atomica11y-skills-web-nav-popover
title: "Nav popover button"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/nav-popover/
---

[Source material](https://www.atomica11y.com/accessible-web/nav-popover/)

# Web Nav popover button skills



## How to test a nav popover button 

Given that I am on a screen with a nav popover button

### 1. Keyboard only

- WHEN I use the tab key to move focus to a menu button

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar and/or enter key to activate a menu button
 
  - I SEE the menu expands/collapses

- THEN when I use the tab key to move focus to a menu option
 
  - I SEE each option is focused

- OR when I use the tab key to move focus to the end of the options
 
  - I SEE focus leaves the menu, I am not trapped in the menu


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a menu button

  - I HEAR its purpose is clear

  - I HEAR the menu button identifies its role as button, each option identifies its role as link

  - I HEAR menu button expresses its state (expanded/collapsed)

- THEN when I use the spacebar and/or enter key to activate a menu button
 
  - I HEAR the menu expands/collapses

- THEN when I use the tab key to move focus to a menu option
 
  - I HEAR each option is focused

- OR when I use the tab key to move focus to the end of the options
 
  - I HEAR focus leaves the menu, i am not trapped in the menu


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a menu button

  - I HEAR its purpose is clear

  - I HEAR the menu button identifies its role as button, each option identifies its role as link

  - I HEAR menu button expresses its state (expanded/collapsed)

- THEN when I doubletap with the button in focus
 
  - I HEAR the menu expands/collapses


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Nav popover button

Nav popover button usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a popover to reveal navigation links.
- Use a button to toggle the popover.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a nav popover button more effectively.

- Do not use menu type roles unless building an application-style menu.
- Do not trap focus inside the popover.
- Do not add arrow key event menu style functionality.


### Nav popover button misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a nav popover button. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A navigation popover is not the same as a WAI-ARIA menu widget.
- Navigation with popovers does not require menu roles.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16