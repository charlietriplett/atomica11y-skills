---
id: accessibility-skills-web-dialog-alert
title: "Dialog alert"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/dialog-alert/
---

[Source material](https://www.atomica11y.com/accessible-web/dialog-alert/)

# Web Dialog alert skills



## How to test a dialog alert 

Given that I am on a screen with a dialog alert

### 1. Keyboard only

- WHEN I use an action that triggers an alert dialog

  - I SEE the dialog opens

- THEN when I use the arrow keys
 
  - I SEE content in the dialog is browsed in meaningful order and does not leave the dialog

- THEN when I use the tab key
 
  - I SEE focus moves to interactive controls inside the dialog


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use an action that triggers an alert dialog

  - I HEAR the dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to a meaningful place

  - I HEAR when open, content behind the modal remains inert

- THEN when I use the arrow keys
 
  - I HEAR content in the dialog is browsed in meaningful order and does not leave the dialog

- THEN when I use the tab key
 
  - I HEAR focus moves to interactive controls inside the dialog


### 3. Mobile screenreader

- WHEN I use a screenreader AND I perform an action that triggers an alert dialog

  - I HEAR the dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to a meaningful place

  - I HEAR when open, content behind the modal remains inert

- THEN when I doubletap with the button in focus
 
  - I HEAR the dialog opens

- THEN when I swipe within the dialog
 
  - I HEAR focus stays trapped in the dialog


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Dialog alert

Dialog alert usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use an alert dialog to interrupt the user journey for urgent or critical tasks that require immediate attention and action.
- Use an alert dialog to confirm destructive actions like deleting an account or to communicate important warnings.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a dialog alert more effectively.

- Do not use an alert dialog for non-critical or routine information.
- Do not use an alert dialog to save space or as a substitute for inline notifications.
- Do not cover the entire view width and view height of the page with an alert dialog.
- Do not stack multiple dialogs.


### Dialog alert misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a dialog alert. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.



> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15