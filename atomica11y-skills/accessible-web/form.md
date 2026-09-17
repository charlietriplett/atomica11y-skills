---
id: atomica11y-skills-web-form
title: "Form"
description: Code and test accessible Web Form. Use when people enter, review, and submit related information.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/form/
---

[Source material](https://www.atomica11y.com/accessible-web/form/)

# Web Form skills



## How to test a form 

Given that I am on a screen with a form

### 1. Keyboard only

- WHEN  I use the tab key to move focus to a control in the form
 
  - I SEE focus moves to the control (but the form itself does not receive focus)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use screen reader landmark shortcuts

  - I HEAR it is discoverable as a form

  - I HEAR its purpose is clear

- WHEN  I use the tab key to move focus to a control in the form
 
  - I HEAR focus moves to the control (but the form itself does not receive focus)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I use screen reader shortcuts 

  - I HEAR it is discoverable as a form

  - I HEAR its purpose is clear

- OR WHEN  I swipe to move focus to a control in the form
 
  - I HEAR focus moves to the control (but the form itself does not receive focus)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Form

Form usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a form to group related inputs required to complete a transaction or submit data.
- Use a form to group related filter inputs and controls.
- Use a form to group search input inputs and controls.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a form more effectively.

- Do not place form inputs in multiple columns. This only makes the form more difficult to use.
- Do not auto-focus the first input on page load. This is disorienting for people using a screen reader.
- Do not place submit buttons in a sidebar unless there is also a submit button at the bottom of the form where people expect it.


### Form misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a form. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- There is no advantage to cramming a form into multiple columns to save space, and doing so severely hinders users with low vision. People are accustomed to scrolling vertically.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17