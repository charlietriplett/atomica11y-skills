---
id: atomica11y-skills-web-strikethrough
title: "Strikethrough content"
description: Code and test accessible Web Strikethrough content. Use when Web text is visually struck through to indicate removed or unavailable content.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/strikethrough/
---

[Source material](https://www.atomica11y.com/accessible-web/strikethrough/)

# Web Strikethrough content skills



## How to test a strikethrough content 

Given that I am on a screen with a strikethrough content

### 1. Keyboard only

- WHEN I use the arrow key to browse the content

  - I SEE the content comes into view


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow key to browse the content

  - I HEAR the content makes sense and is in logical order


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse the content

  - I HEAR the content makes sense and is in logical order


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Strikethrough content

Strikethrough content usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Most of the time, this isn’t worth the hassle as extra hidden code must be thoughtfully implemented. Even if it’s implemented correctly the first time, some update will likely cause the accessibility to be lost.
- Use strikethrough to indicate content that is no longer accurate, has been removed, or has been updated.
- Ensure the deletion is programmatically conveyed to screen readers using semantic HTML or visually hidden text.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a strikethrough content more effectively.

- Do not rely on CSS text-decoration line-through alone or <code class="language-plaintext highlighter-rouge">&lt;s&gt;</code> markup, as screen readers will not announce the visual styling.
- Do not try to override <code class="language-plaintext highlighter-rouge">&lt;s&gt;</code> markup name for the screen reader with aria-label. Some screenreaders will not read <code class="language-plaintext highlighter-rouge">aria-label</code> from non-interactive components.


### Strikethrough content misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a strikethrough content. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- The strikethrough <code class="language-plaintext highlighter-rouge">&lt;s&gt;</code> markup is ignored by screen readers. Instead, use visually hidden text to indicate the state of the strikethrough text.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17