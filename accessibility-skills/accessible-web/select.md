---
id: accessibility-skills-web-select
title: "Select dropdown listbox"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/select/
---

# Web Select dropdown listbox skills



## How to test a select dropdown listbox 

Given that I am on a screen with a select dropdown listbox

### 1. Keyboard only

- WHEN I use the tab key to move focus to a select

  - I SEE focus is strongly visually indicated

- THEN when I use the arrow keys to select an option
 
  - I SEE the selected option is changed

- THEN when I use the escape key when the select is open 
 
  - I SEE it collapses and focus moves to the select


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a select

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a select, popup, menu/submenu, listbox or combobox

  - I HEAR hints or errors are read after the label and related inputs include a group name (ex: account settings)

  - I HEAR it indicates which option is selected and if disabled/dimmed/unavailable

- THEN when I use the arrow keys to select an option
 
  - I HEAR the selected option is changed

- THEN when I use the escape key when the select is open 
 
  - I HEAR it collapses and focus moves to the select


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a select

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a select, popup, menu/submenu, listbox or combobox

  - I HEAR hints or errors are read after the label and related inputs include a group name (ex: account settings)

  - I HEAR it indicates which option is selected and if disabled/dimmed/unavailable

- THEN when I doubletap with the select in focus
 
  - I HEAR the options can be selected


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Select dropdown listbox

Select dropdown listbox usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a select when choosing one option from a logically ordered list (e.g., numbers, dates, levels, rankings).
- Use a select when the option list is long, logically ordered and showing all choices would overwhelm the layout.
- Use a select for filtering or sorting.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a select dropdown listbox more effectively.

- Do not replace a native select with a custom script-based dropdown.
- Do not use a select when non-ordered options exist; use radio buttons instead.
- Do not remove the visible label.
- Do not use a select for binary on/off settings; use a checkbox or toggle switch instead.
- Do not use a multi-select. Most users cannot be expected to understand modifier-key interaction.


### Select dropdown listbox misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a select dropdown listbox. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A dropdown is not automatically better than many radio buttons; hiding options can reduce comprehension.
- Styling a custom dropdown does not improve usability; people just want it to work reliably.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13