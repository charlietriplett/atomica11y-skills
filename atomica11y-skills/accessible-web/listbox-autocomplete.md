---
id: atomica11y-skills-web-listbox-autocomplete
title: "Autocomplete input with listbox"
description: Code and test accessible Web Autocomplete input with listbox. Use when people type to select a value from suggested Web options.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/listbox-autocomplete/
---

[Source material](https://www.atomica11y.com/accessible-web/listbox-autocomplete/)

# Web Autocomplete input with listbox skills



## How to test an autocomplete input with listbox 

Given that I am on a screen with an autocomplete input with listbox

### 1. Keyboard only

- WHEN I use the tab key to move focus to the text input

  - I SEE focus is strongly visually indicated

- THEN when I use the arrow keys to select an option
 
  - I SEE the selected option is the new text input value

- THEN when I use the enter key
 
  - I SEE the selected option is changed and focus returns to the text input

- THEN when I use the escape key when the select is open 
 
  - I SEE it collapses and focus moves to the text input


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to the text input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a select, popup, menu/submenu, listbox or combobox

  - I HEAR its label is read and selected options are read

  - I HEAR it indicates the value of the text input 

- THEN when I use the arrow keys to select an option
 
  - I HEAR the selected option is the new text input value

- THEN when I use the enter key
 
  - I HEAR the selected option is changed and focus returns to the text input

- THEN when I use the escape key when the select is open 
 
  - I HEAR it collapses and focus moves to the text input


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a select

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a select, popup, menu/submenu, listbox or combobox

  - I HEAR its label is read and selected options are read

  - I HEAR it indicates the value of the text input 

- THEN when I doubletap with the select in focus
 
  - I HEAR the selected option is changed


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Autocomplete input with listbox

Autocomplete input with listbox usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use autosuggest to suggest what the application thinks or hopes the user is searching for.
- Autocomplete is the native browser action for filling fields based on values people have previously entered or stored.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a autocomplete input with listbox more effectively.

- Do not hide the listbox DOM from screen readers while visually displaying it.
- Do not create a custom listbox when a text input with a datalist will do.


### Autocomplete input with listbox misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a autocomplete input with listbox. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Custom listboxes are not easy to maintain over time. Future development updates will eventually break accessibility.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17