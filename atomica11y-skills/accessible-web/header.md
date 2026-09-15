---
id: atomica11y-skills-web-header
title: "Header / banner landmark"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/header/
---

[Source material](https://www.atomica11y.com/accessible-web/header/)

# Web Header / banner landmark skills



## How to test a header / banner  

Given that I am on a screen with a header / banner landmark

### 1. Keyboard only

- WHEN  I use the tab key to move focus to a control in the header
 
  - I SEE focus moves to the control (but the header landmark itself does not receive focus)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use landmark shortcuts

  - I HEAR it is discoverable as a banner landmark

  - I HEAR it has no name, only a role because there should be only one

- WHEN  I use the tab key to move focus to a control in the header
 
  - I HEAR focus moves to the control (but the header landmark itself does not receive focus)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I landmark shortcuts

  - I HEAR it is discoverable as a banner landmark

  - I HEAR it has no name, only a role because there should be only one

- OR WHEN  I swipe to move focus to a control in the header
 
  - I HEAR focus moves to the control (but the header itself does not receive focus)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Header / banner landmark

Header / banner landmark usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a &lt;header&gt; element as the page’s banner landmark.
- Use a &lt;header&gt; to contain the site title, logo, and main navigation content when appropriate.
- Include primary navigation inside the header when appropriate.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a header / banner landmark more effectively.

- Do not give the page-level &lt;header&gt; an accessible name.
- Do not focus the &lt;header&gt; element itself.
- Do not use multiple banner-level headers on a single page; while this is technically valid markup it’s not useful for people using screen readers.


### Header / banner landmark misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a header / banner landmark. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- The &lt;header&gt; element is not purely visual; it creates a banner landmark.
- The &lt;header&gt; landmark does not require a name or additional role.
- The header landmark itself does not receive focus; only controls inside it do.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15