---
id: atomica11y-skills-web-checkbox
title: "Checkbox"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/checkbox/
---

[Source material](https://www.atomica11y.com/accessible-web/checkbox/)

# Web Checkbox skills



## How to test a checkbox 

Given that I am on a screen with a checkbox

### 1. Keyboard only

- WHEN I use the tab key to move focus to a checkbox

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar to activate the checkbox
 
  - I SEE the state is changed


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a checkbox

  - I HEAR its label and purpose is clear

  - I HEAR it identifies its role of checkbox

  - I HEAR it expresses its state (checked/unchecked)

  - I HEAR hints or errors are read after the label and related inputs include a group name (ex: account settings)

- THEN when I use the spacebar to activate the checkbox
 
  - I HEAR the state is changed


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a checkbox input

  - I HEAR its label and purpose is clear

  - I HEAR it identifies its role of checkbox

  - I HEAR it expresses its state (checked/unchecked)

  - I HEAR hints or errors are read after the label and related inputs include a group name (ex: account settings)

- THEN when I doubletap with the checkbox in focus
 
  - I HEAR the state is changed


### 4. Device settings

- WHEN I use custom font settings I SEE text resizes up to 200% without losing information


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Checkbox

Checkbox usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- A checkbox represents one independent choice. Use checkboxes only when more than one option may be selected.
- If users may select more than one option, use checkboxes.
- If users may select only one option, use radio buttons.
- Use a checkbox to affirm a choice or agree to an option, rather than to decline or refuse it.
- Use a named checkbox group when multiple selections are allowed.
- Use checkboxes when the options are not mutually exclusive.
- Use a single checkbox for confirming agreement (e.g., “I agree to the terms”), not a radio button.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a checkbox more effectively.

- Do not use a checkbox when only one option in a group can be selected; use radio buttons instead.
- Do not change the accessible name or visual label when the checkbox state changes.


### Checkbox misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a checkbox. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Never use checkboxes for mutually exclusive choices. Use a radio button group instead.
- A toggle switch is not interchangeable with a checkbox unless the intent is specifically an on/off state.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16