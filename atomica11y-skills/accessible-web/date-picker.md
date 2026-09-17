---
id: atomica11y-skills-web-date-picker
title: "Date picker dialog"
description: Code and test accessible Web Date picker dialog. Use when people select a calendar date.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/date-picker/
---

[Source material](https://www.atomica11y.com/accessible-web/date-picker/)

# Web Date picker dialog skills



## How to test a date picker dialog 

Given that I am on a screen with a date picker dialog

### 1. Keyboard only

- WHEN I use the tab key to move focus to the date dialog button

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar and/or enter key
 
  - I SEE the date picker dialog appears

- THEN when I use the arrow keys
 
  - I SEE the selection moves through next/previous dates

- THEN when I use the home/end key
 
  - I SEE the selection moves to the first/last day of the current week

- THEN when I use the page up/down key
 
  - I SEE the grid of dates moves to the next/previous month

- THEN when I use shift key + page up/down
 
  - I SEE the grid of dates moves to the next/previous year

- THEN when I use the spacebar and/or enter key
 
  - I SEE the button or selection is activated

- THEN when I use the escape key
 
  - I SEE the date picker dialog disappears and focus returns to the date dialog button


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to the date dialog button

  - I HEAR the purpose of each control is clear

  - I HEAR buttons identify as buttons, 
dialog identifies itself dialog or modal, 
date grid table may identify itself as table or grid

  - I HEAR the launch button indicates it has a popup, menu or dialog; days are announced with month and year

  - I HEAR date options express state (pressed, selected, disabled/dimmed)

- THEN when I use the spacebar and/or enter key
 
  - I HEAR the date picker dialog appears

- THEN when I use the arrow keys
 
  - I HEAR the selection moves through next/previous dates

- THEN when I use the home/end key
 
  - I HEAR the selection moves to the first/last day of the current week

- THEN when I use the page up/down key
 
  - I HEAR the grid of dates moves to the next/previous month

- THEN when I use shift key + page up/down
 
  - I HEAR the grid of dates moves to the next/previous year

- THEN when I use the spacebar and/or enter key
 
  - I HEAR the button or selection is activated

- THEN when I use the escape key
 
  - I HEAR the date picker dialog disappears and focus returns to the date dialog button


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on the date dialog button

  - I HEAR the purpose of each control is clear

  - I HEAR buttons identify as buttons, 
dialog identifies itself dialog or modal, 
date grid table may identify itself as table or grid

  - I HEAR the launch button indicates it has a popup, menu or dialog; days are announced with month and year

  - I HEAR date options express state (pressed, selected, disabled/dimmed)

- THEN when I doubletap with the button in focus
 
  - I HEAR the date picker dialog appears

- THEN when I swipe through the dialog
 
  - I HEAR the date options and controls come into focus

- THEN when I doubletap with the selection or button in focus
 
  - I HEAR the intended action occurs


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Date picker dialog

Date picker dialog usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a date picker popup calendar when users need to discover an available date.
- Use a custom calendar widget only when grid keyboard and screen reader navigation is supported.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a date picker dialog more effectively.

- Do not use date pickers without manual text entry as a fallback.
- Do not use date pickers for choosing general dates in the distant past (like employment dates or college graduation). A select or text input is usually more appropriate.


### Date picker dialog misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a date picker dialog. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Custom date pickers are universally better than simply entering a date. Power users performing administrative date entry are often faster at typing than navigating a calendar.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17