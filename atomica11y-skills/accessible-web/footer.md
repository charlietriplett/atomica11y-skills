---
id: atomica11y-skills-web-footer
title: "Footer / contentinfo landmark"
description: Code and test accessible Web Footer / contentinfo landmark. Use when a site or page footer contains supporting navigation or information.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/footer/
---

[Source material](https://www.atomica11y.com/accessible-web/footer/)

# Web Footer / contentinfo landmark skills



## How to test a footer / contentinfo  

Given that I am on a screen with a footer / contentinfo landmark

### 1. Keyboard only

- WHEN  I use the tab key to move focus to a control in the footer
 
  - I SEE focus moves to the control (but the footer landmark itself does not receive focus)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use landmark shortcuts

  - I HEAR it is discoverable as a contentinfo or footer landmark

  - I HEAR it has no name, only a role because there should be only one

- WHEN  I use the tab key to move focus to a control in the footer
 
  - I HEAR focus moves to the control (but the footer landmark itself does not receive focus)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I use screen reader shortcuts 

  - I HEAR it is discoverable as a contentinfo or footer landmark

  - I HEAR it has no name, only a role because there should be only one

- OR WHEN  I swipe to move focus to a control in the footer
 
  - I HEAR focus moves to the control (but the footer itself does not receive focus)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Footer / contentinfo landmark

Footer / contentinfo landmark usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a &lt;footer&gt; element as the page’s contentinfo landmark.
- Use a &lt;footer&gt; to contain legal information and/or a mini site map.
- Include site map navigation inside the footer when appropriate.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a footer / contentinfo landmark more effectively.

- Do not give the footer an accessible name.
- Do not focus the &lt;footer&gt; element itself; screen readers can identify it with shortcuts.
- Do not use multiple page-level footer landmarks; there should be only one &lt;footer&gt; per HTML document.
- Do not add redundant role=”contentinfo” to &lt;footer&gt;.


### Footer / contentinfo landmark misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a footer / contentinfo landmark. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- The &lt;footer&gt; element is not purely visual; it creates a contentinfo landmark discoverable for screen reader shortcuts.
- The &lt;footer&gt; landmark does not require a name because there should only be one.
- The footer landmark itself does not receive tab focus, but it is targetable using a skip link.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17