---
id: atomica11y-skills-web-nav
title: "Navigation landmark"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/nav/
---

[Source material](https://www.atomica11y.com/accessible-web/nav/)

# Web Navigation landmark skills



## How to test a navigation  

Given that I am on a screen with a navigation landmark

### 1. Keyboard only

- WHEN  I use the tab key to move focus to a control in the navigation
 
  - I SEE focus moves to the control (but the navigation landmark itself does not receive focus)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use landmark shortcuts

  - I HEAR it is discoverable as a navigation landmark

  - I HEAR if there are multiple navigations present, its purpose is unique and clear

- WHEN  I use the tab key to move focus to a control in the navigation
 
  - I HEAR focus moves to the control (but the navigation landmark itself does not receive focus)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I use screen reader shortcuts 

  - I HEAR it is discoverable as a navigation landmark

  - I HEAR if there are multiple navigations present, its purpose is unique and clear

- OR WHEN  I swipe to move focus to a control in the navigation
 
  - I HEAR focus moves to the control (but the navigation itself does not receive focus)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Navigation landmark

Navigation landmark usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code> to define major navigation landmarks that help users move through the system.
- Use <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code> to group primary navigation, category navigation, breadcrumbs, pagination, or in-page section navigation.
- Ensure each <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code>communicates its purpose clearly when multiple navigation regions exist (e.g., Main, Breadcrumb, Categories, Site map).
- Keep navigation structure consistent across pages to support spatial memory and predictability.
- Ensure navigation order reflects meaningful progression or grouping.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a navigation landmark more effectively.

- Do not use multiple unnamed navigation regions, as this will misdirect users of assistive technologies. Instead, give every <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code> a name (e.g., Main, Breadcrumb, Categories, Site map).
- Do not rely solely on visual layout to communicate navigation structure; ensure semantic and assistive technology support.
- Do not add menu, menubar, or menuitem roles to a <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code> unless you are building actual application-style software (e.g., Gmail, TurboTax).
- Do not add tabgroup roles to a <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code> even if it uses tab like styling.


### Navigation landmark misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a navigation landmark. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code> should not use a menu roles unless you are building full on application-style software.
- A <code class="language-plaintext highlighter-rouge">&lt;nav&gt;</code> landmark itself does not receive tab focus, but it can be targetable using a skip link.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15