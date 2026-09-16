---
id: atomica11y-skills-web-main
title: "Main landmark"
description: Code and test accessible Web Main landmark. Use when identifying the primary Web content of a page.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/main/
---

[Source material](https://www.atomica11y.com/accessible-web/main/)

# Web Main landmark skills



## How to test a main  

Given that I am on a screen with a main landmark

### 1. Keyboard only

- THEN when I use the tab key to move focus to a control in the main
 
  - I SEE focus moves to the control (but the landmark itself does not receive focus)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use landmark shortcuts

  - I HEAR it is discoverable as a main landmark

  - I HEAR it has no name, only a role because there should be only one

- THEN when I use the tab key to move focus to a control in the main
 
  - I HEAR focus moves to the control (but the landmark itself does not receive focus)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I use screen reader shortcuts 

  - I HEAR it is discoverable as a main landmark

  - I HEAR it has no name, only a role because there should be only one

- OR WHEN  I swipe to move focus to a control in the landmark
 
  - I HEAR focus moves to the control (but the landmark itself does not receive focus)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Main landmark

Main landmark usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> element to define the primary content of the document.
- Use only one <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> landmark per page.
- Place the main content between the header/nav and footer landmarks.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a main landmark more effectively.

- Do not give the <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> landmark an accessible name.
- Do not focus the <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> element itself.
- Do not use multiple <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> landmarks on the same page.
- Do not use <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> as a generic layout container.


### Main landmark misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a main landmark. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- The <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> element is not a visual wrapper; it creates a programmatically discoverable landmark with screen reader shortcuts.
- The <code class="language-plaintext highlighter-rouge">&lt;main&gt;</code> landmark does not require a name because there should only be one.
- The main landmark itself does not receive tab focus; only interactive elements inside it do. But it is targetable using a skip link.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16