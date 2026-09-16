---
id: atomica11y-skills-web-list
title: "List"
description: Code and test accessible Web List\". Use when related Web items are presented as a list.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/list/
---

[Source material](https://www.atomica11y.com/accessible-web/list/)

# Web List skills



## How to test a list 

Given that I am on a screen with a list

### 1. Keyboard only

- WHEN I use the arrow key to browse to a list

  - I SEE the list comes into view

- WHEN  I use the tab key
 
  - I SEE nothing happens to the list itself because lists must NOT be focusable


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow key to browse to a list

  - I HEAR it identifies itself as a list

  - I HEAR it declares the number of items in the list

- WHEN  I use the tab key
 
  - I HEAR nothing happens to the list itself because lists must not be focusable


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse a list

  - I HEAR it identifies itself as a list

  - I HEAR it declares the number of items in the list


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a List

List usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a list when presenting any collection of related items.
- Use a list to improve visual scanning and comprehension of related content.
- Use a list when each item in a collection has equal importance and priority.
- Use a list when screen reader users will benefit from list semantics because item counts and list boundaries are announced.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a list more effectively.

- Do not use an unordered list <code class="language-plaintext highlighter-rouge">&lt;ul&gt;</code> when the sequence of items is important; use an ordered list <code class="language-plaintext highlighter-rouge">&lt;ol&gt;</code> instead.
- Do not create lists with only a single item, unless it’s part of dynamic content and expansion can be expected.
- Do not use lists solely for visual indentation or emphasis.
- Do not use typed bullets, hyphens, emojis or decorative characters in place of semantic list markup.


### List misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a list. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Visual spacing alone does not programmatically communicate the relationships between items as effectively as semantic list markup.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16