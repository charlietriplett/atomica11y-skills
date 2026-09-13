---
id: accessibility-skills-web-button
title: "Button"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/button/
---

# Web Button skills



## How to test a button 

Given that I am on a screen with a button

### 1. Keyboard only

- WHEN I use the tab key to move focus to a button

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar and/or enter key to activate the button
 
  - I SEE the intended action occurs


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a button

  - I HEAR its purpose is clear

  - I HEAR it identifies its role of button

  - I HEAR it expresses its state if applicable (expanded / collapsed, pressed, disabled / dimmed / unavailable)

- THEN when I use the spacebar and/or enter key to activate the button
 
  - I HEAR the intended action occurs


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a button

  - I HEAR its purpose is clear

  - I HEAR it identifies its role of button

  - I HEAR it expresses its state if applicable (expanded / collapsed, pressed, disabled / dimmed / unavailable)

- THEN when I doubletap with the button in focus
 
  - I HEAR the intended action occurs


### 4. Device settings

- WHEN I use custom font settings I SEE text resizes up to 200% without losing information


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Button

Button usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- If it goes somewhere, it’s a link. If it does something, it’s a button.
- Use a button to make something happen right now on the same page like submitting, saving, continuing to a next step, or revealing something related to what you’re doing.
- Use a button to submit a form, even when submission navigates to a confirmation page.
- Use a button for opening or closing a dialog modal or popover.
- Use a button for expanding or collapsing custom content (like an expander accordion).
- Use a button to move to the next step on the same page (without changing the URL).
- Use a button to trigger a change in the current page (like showing or hiding something).


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a button more effectively.

- Do not use a button to go to another page URL without submitting a form. Instead use a link.
- Do not use a button to skip to a section on the same page. Instead use a link.
- Do not use vague or unclear button names like “Click Here.” Instead, describe the specific purpose of the button.
- Do not change the button name in combination with ARIA states. For example, if a button expands and collapses information, don’t change the button name from “Show” to “Hide” and include aria-expanded attributes. Do one or the other. Never both.


### Button misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a button. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Just because a link looks like a button doesn’t mean it is one. Question the function. Does clicking the control navigate to another page or location within a page without submitting or saving information? Then use a link, not a button.
- Just because a form control is styled like a button doesn’t mean it is one. Question the function. Is it selecting one from a group? Use radio buttons. Is it selecting multiple from a group? Use checkboxes.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13