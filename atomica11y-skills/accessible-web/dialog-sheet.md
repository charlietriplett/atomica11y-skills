---
id: atomica11y-skills-web-dialog-sheet
title: "Dialog sheet"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/dialog-sheet/
---

[Source material](https://www.atomica11y.com/accessible-web/dialog-sheet/)

# Web Dialog sheet skills



## How to test a dialog sheet 

Given that I am on a screen with a dialog sheet

### 1. Keyboard only

- WHEN I use the tab key to move focus to the launch button and use spacebar and/or enter key to activate the button

  - I SEE the sheet dialog opens and is in focus

- THEN when I use the arrow keys
 
  - I SEE content in the sheet dialog is browsed in meaningful order and does not leave the dialog

- THEN when I use the tab key
 
  - I SEE focus moves to interactive controls in the sheet dialog

- THEN when I use the escape key
 
  - I SEE focus returns to the launch button

- OR when I use the tab key to move focus to the dismiss/close button <strong>AND THEN</strong> use the spacebar or enter key to activate the dismiss/close button
 
  - I SEE focus returns to the launch button


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to the launch button and use spacebar and/or enter key to activate the button

  - I HEAR the sheet dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to the launch button

  - I HEAR when open, content behind the modal remains inert

- THEN when I use the arrow keys
 
  - I HEAR content in the sheet dialog is browsed in meaningful order and does not leave the dialog

- THEN when I use the tab key
 
  - I HEAR focus moves to interactive controls in the sheet dialog

- THEN when I use the escape key
 
  - I HEAR focus returns to the launch button

- OR when I use the tab key to move focus to the dismiss/close button <strong>AND THEN</strong> use the spacebar or enter key to activate the dismiss/close button
 
  - I HEAR focus returns to the launch button


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus to the launch button

  - I HEAR the sheet dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to the launch button

  - I HEAR when open, content behind the modal remains inert

- THEN when I doubletap with the button in focus
 
  - I HEAR the dialog opens

- THEN when I swipe within the sheet dialog
 
  - I HEAR focus stays trapped in the sheet dialog

- THEN when I swipe to move focus to the dismiss/close button <strong>AND THEN</strong> double tap on the close button
 
  - I HEAR focus returns to the launch button


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Dialog sheet

Dialog sheet usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a dialog modal to interrupt the user journey for some singular important purpose or task that requires the user to focus.
- Use a bottom or side sheet on mobile devices to present secondary actions without taking the user completely out of their current context.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a dialog sheet more effectively.

- Do not use a dialog modal simply to save space.
- Do not stack modals. Opening a modal from inside another modal disorients, confuses, and frustrates people.
- Do not use a dialog modal for showing routine content.


### Dialog sheet misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a dialog sheet. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A dialog modal is not the best way to grab attention. Carefully crafted UX writing, design, and structure are what direct people’s attention.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16