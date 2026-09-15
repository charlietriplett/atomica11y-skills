---
id: atomica11y-skills-web-radio
title: "Radio button"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/radio/
---

[Source material](https://www.atomica11y.com/accessible-web/radio/)

# Web Radio button skills



## How to test a radio button 

Given that I am on a screen with a radio button

### 1. Keyboard only

- WHEN I use the tab key to move focus to a radio group

  - I SEE focus is strongly visually indicated on the first unselected option or the selected option

- THEN when I use the arrow keys to select a radio button
 
  - I SEE the state is changed

- OR WHEN  I use the spacebar to activate a focused radio button
 
  - I SEE the radio button is selected.


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a radio group

  - I HEAR its label and purpose is clear

  - I HEAR it identifies itself as a radio button

  - I HEAR it expresses its state (selected, checked, disabled/dimmed)

  - I HEAR hints or errors are read after the label and related inputs include a group name (ex: shipping options)

- THEN when I use the arrow keys to select a radio button
 
  - I HEAR the state is changed

- OR WHEN  I use the spacebar to activate a focused radio button
 
  - I HEAR the radio button is selected.


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a radio button

  - I HEAR its label and purpose is clear

  - I HEAR it identifies itself as a radio button

  - I HEAR it expresses its state (selected, checked, disabled/dimmed)

  - I HEAR hints or errors are read after the label and related inputs include a group name (ex: shipping options)

- THEN when I doubletap with the radio in focus
 
  - I HEAR the state is changed


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Radio button

Radio button usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- If users may select more than one option, use checkboxes.
- If users may select only one option, use radio buttons.
- Radio buttons represent mutually exclusive options.
- Use a named radio group (fieldset + legend or programmatic group name) to describe the shared question.
- Use radio buttons when users should see all available options at once.
- Use radio buttons over a select when the options are not logically ordered.
- If options are logically ordered and numerous, consider a select instead.
- The group label must describe the question being answered.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a radio button more effectively.

- Do not auto-advance on change of radio selection; this blocks people using a keyboard who must cycle through each option to select.
- Do not place focusable controls inbetween radio options or inside labels.
- Do not use radio buttons when multiple selections are allowed; use checkboxes instead.
- Do not omit the group label (fieldset + legend or accessible group name).
- Do not dynamically change a radio option’s accessible name when the selection changes.
- Do not use a single radio button for a yes/no agree/disagree on/off setting because it cannot be unselected.


### Radio button misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a radio button. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- If there are many options, a dropdown select is not automatically better; radio buttons offer visibility of non-logically ordered options imporoving comprehension.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15