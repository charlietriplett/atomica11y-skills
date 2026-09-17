---
id: atomica11y-skills-web-card
title: "Card box"
description: Code and test accessible Web Card box\". Use when related content or actions are grouped in a contained surface.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/card/
---

[Source material](https://www.atomica11y.com/accessible-web/card/)

# Web Card box skills



## How to test a card box 

Given that I am on a screen with a card box

### 1. Keyboard only

- WHEN I use the arrow key to browse to a card

  - I SEE the card scrolls into view

- WHEN  I use the tab key
 
  - I SEE individual controls are focusable (but not the card itself)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow key to browse to a card

  - I HEAR the card&#39;s purpose is clear from its heading

  - I HEAR the card itself has no role, only the content inside

- WHEN  I use the tab key
 
  - I HEAR individual controls are focusable (but not the card itself)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse to a card

  - I HEAR the card&#39;s purpose is clear from its heading

  - I HEAR the card itself has no role, only the content inside


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Card box

Card box usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a card to group related content visually and semantically.
- Use a card to highlight specific content or actions within a page.
- Ensure only the interactive portions inside the card are focusable.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a card box more effectively.

- Do not use a card as a single focusable element. Instead, ensure only the interactive portions inside the card are focusable.
- Do not assign a semantic role to the card itself. Focus on the content inside.
- Do not overload a card with too much information, making it difficult to navigate or understand.
- Do not remove individual links in favor of one large clickable wrapper.


### Card box misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a card box. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Cards are not inherently interactive with assistive technology even if they are clickable with a mouse. Interactivity for assistive technology comes from the elements inside the card, not the card itself.
- Cards do not require a specific role or interaction unless their content or purpose demands it. They are primarily a visual and organizational tool.
- Cards are not a replacement for proper semantic structure. Ensure the content inside the card follows semantic HTML principles.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17