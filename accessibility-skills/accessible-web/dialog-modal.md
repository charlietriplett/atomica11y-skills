---
id: accessibility-skills-web-dialog-modal
title: "Dialog modal"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/dialog-modal/
---

[Source material](https://www.atomica11y.com/accessible-web/dialog-modal/)

# Web Dialog modal skills



## How to test a dialog modal 

Given that I am on a screen with a dialog modal

### 1. Keyboard only

- WHEN I use the tab key to move focus to the launch button and use spacebar and/or enter key to activate the button

  - I SEE the dialog opens

- THEN when I use the arrow keys
 
  - I SEE content is browsed in meaningful order, content behind the dialog remains inert

- THEN when I use the tab key
 
  - I SEE focus moves to interactive controls in the dialog, content behind the dialog remains inert

- THEN when I use the escape key
 
  - I SEE focus returns to the launch button

- OR when I use the tab key to move focus to the dismiss/close button AND THEN use the spacebar or enter key to activate the dismiss/close button
 
  - I SEE focus returns to the launch button


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to the launch button and use spacebar and/or enter key to activate the button

  - I HEAR the dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to the launch button

  - I HEAR when open, content behind the dialog remains inert

- THEN when I use the arrow keys
 
  - I HEAR content is browsed in meaningful order, content behind the dialog remains inert

- THEN when I use the tab key
 
  - I HEAR focus moves to interactive controls in the dialog, content behind the dialog remains inert

- THEN when I use the escape key
 
  - I HEAR focus returns to the launch button

- OR when I use the tab key to move focus to the dismiss/close button AND THEN use the spacebar or enter key to activate the dismiss/close button
 
  - I HEAR focus returns to the launch button


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus to the launch button

  - I HEAR the dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to the launch button

  - I HEAR when open, content behind the dialog remains inert

- THEN when I doubletap with the button in focus
 
  - I HEAR the dialog opens

- THEN when I swipe within the dialog
 
  - I HEAR focus stays trapped in the dialog

- THEN when I swipe to move focus to the dismiss/close button AND THEN double tap on the close button
 
  - I HEAR focus returns to the launch button


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Dialog modal

Dialog modal usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a dialog modal to interrupt the user journey for some singularly important purpose, content or task that requires the user to focus.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a dialog modal more effectively.

- Do not use a dialog modal simply to save space.
- Do not use a dialog modal for showing routine content.
- Do not use a modal as a substitute for a page, route, or full workflow.
- Do not put multi-step, high-friction, or cognitively demanding forms in a dialog modal unless there is a documentable business reason to do so (e.g. conversion data). If you’re compelled to do so, ensure progress is saved if the modal is accidentally closed
- Do not cover the entire view width and view height of the page with a dialog modal; this causes sighted people to believe they are on a new page and instead of closing the dialog modal they will try to go back.
- Do not stack modals. Opening one modal from another disorients, confuses, and frustrates people.
- Do not use a dialog modal to show help text, tooltips, or more info popups. If the content does not fit in the available space, write tighter contextual inline help. If that isn’t possible, use an accordion expander, a popover, or a dedicated page instead.
- Do not use the popover API to control dialog modal; instead use <dialog> with modal.showModal();</dialog>
- Do not apply tabindex=”-1” or aria-hidden to inert background elements.


### Dialog modal misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a dialog modal. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A dialog modal is not the best way to get attention. Carefully crafted UX writing, design and structure are what direct people’s attention.
- Using role=”dialog” on custom elements does not implement full keyboard compatibility. Always use a semantic <dialog> element.</dialog>


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13