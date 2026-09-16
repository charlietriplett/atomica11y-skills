---
id: atomica11y-skills-web-stepper-input
title: "Stepper input"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/stepper-input/
---

[Source material](https://www.atomica11y.com/accessible-web/stepper-input/)

# Web Stepper input skills



## How to test a stepper input 

Given that I am on a screen with a stepper input

### 1. Keyboard only

- WHEN I use the tab key to move focus to the select (+/- buttons are ignored)

  - I SEE focus is strongly visually indicated

- THEN when I use the arrow keys to select an option
 
  - I SEE the selected option is changed

- THEN when I use the escape key when the select is expanded 
 
  - I SEE it collapses and focus moves to the select


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to the select (+/- buttons are ignored)

  - I HEAR its purpose is clear (+/- buttons are ignored)

  - I HEAR it identifies itself as a select, popup button, menu/submenu or combobox

  - I HEAR its label is read with the input

  - I HEAR it indicates when the select is expanded/collapsed, indicates which option is selected

- THEN when I use the arrow keys to select an option
 
  - I HEAR the selected option is changed

- THEN when I use the escape key when the select is expanded 
 
  - I HEAR it collapses and focus moves to the select


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on the select (+/- buttons are ignored)

  - I HEAR its purpose is clear (+/- buttons are ignored)

  - I HEAR it identifies itself as a select, popup button, menu/submenu or combobox

  - I HEAR its label is read with the input

  - I HEAR it indicates when the select is expanded/collapsed, indicates which option is selected

- THEN when I doubletap with the select in focus
 
  - I HEAR the picker/spinner expands

- THEN when I swipe to and doubletap the desired option
 
  - I HEAR the picker/spnner collapses


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Stepper input

Stepper input usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a stepper input for incremental or decremental numeric adjustments.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a stepper input more effectively.

- Do not use steppers that disable manual text entry. Always include a method for direct entry with a semantic input field or select.
- Do not use a stepper to enter large numbers.


### Stepper input misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a stepper input. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Steppers are not faster than typing numbers.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16