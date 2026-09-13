---
id: accessibility-skills-web-link
title: "Link"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/link/
---

# Web Link skills



## How to test a link 

Given that I am on a screen with a link

### 1. Keyboard only

- WHEN I use the tab key to move focus to a link

  - I SEE focus is strongly visually indicated

- THEN when I use the enter key to activate the link
 
  - I SEE my browser goes somewhere


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a link

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a link

- THEN when I use the enter key to activate the link
 
  - I HEAR my browser goes somewhere


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a link

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a link

- THEN when I doubletap with the link in focus
 
  - I HEAR my browser goes somewhere


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Link

Link usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- If it goes somewhere, it’s a link. If it does something, it’s a button.
- Use a link for navigation outcomes such as navigating to another page, jumping to a section on the same page, or accessing an external resource.
- Use a link when the primary purpose is to redirect or navigate to a different page of a website or route in an application, not to perform an action (e.g. Open a dialog or submit a form).
- Use a link for actions like navigating to another page, jumping to a specific section on the same page, or accessing external resources.
- Use a link when the user can reasonably ask, “Where does this take me?”


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a link more effectively.

- Do not use a link to open a modal, dialog, menu, drawer, tooltip, popover, or disclosure; instead use a button.
- Do not use vague or generic link text like “Click Here.” Instead, link descriptive text that clearly indicates the destination or purpose of the link.
- Do not use <code class="language-plaintext highlighter-rouge">href="#"</code> or <code class="language-plaintext highlighter-rouge">href="javascript:void(0)"</code> as href placeholders. These break accessibility and usability expectations.


### Link misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a link. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Just because a link is styled like a button doesn’t mean it’s a button. Question the purpose and intent. If it navigates, it’s a link, not a button.
- Buttons and links do not activate the same ways; Buttons activate with both the Spacebar and Enter keys, while links activate with the Enter key only.
- A form submit button that triggers a confirmation page is still a button, not a link; because its purpose and intent is submitting the form.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13