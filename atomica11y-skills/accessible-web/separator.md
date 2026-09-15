---
id: atomica11y-skills-web-separator
title: "Separator / horizontal rule"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/separator/
---

[Source material](https://www.atomica11y.com/accessible-web/separator/)

# Web Separator / horizontal rule skills



## How to test a separator / horizontal rule 

Given that I am on a screen with a separator / horizontal rule

### 1. Keyboard only

- WHEN I use arrow keys to browse to the separator

  - I SEE the element is skipped entirely. It is completely inert.


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use arrow keys to browse to the separator

  - I HEAR the element is skipped entirely. it is completely inert.


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to the separator

  - I HEAR the element is skipped entirely. it is completely inert.


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Separator / horizontal rule

Separator / horizontal rule usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Don’t use separators unless you have no other reasonable choice.
- Use a separator when, for some inexcusable systematic reason, you’re not able to use css to add a border to an element.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a separator / horizontal rule more effectively.

- Do not allow screen readers to read a separator. Separator should always use <code class="language-plaintext highlighter-rouge">aria-hidden</code> to hide it from screen readers.
- Do not use a separator to create document structure.


### Separator / horizontal rule misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a separator / horizontal rule. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A separator does not create document structure; headings and landmarks create structure.
- Decorative separators should not be exposed to assistive technologies.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15