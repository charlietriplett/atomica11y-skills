---
id: atomica11y-skills-web-image-decorative
title: "Decorative image / icon"
description: Code and test accessible Web Decorative image / icon. Use when an image is visual decoration and conveys no needed information.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/image-decorative/
---

[Source material](https://www.atomica11y.com/accessible-web/image-decorative/)

# Web Decorative image / icon skills



## How to test a decorative image / icon 

Given that I am on a screen with a decorative image / icon

### 1. Keyboard only

- WHEN I use the arrow keys to browse to an image

  - I SEE the image is skipped and ignored


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow keys to browse to an image

  - I HEAR the image is ignored


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse to an image

  - I HEAR the image is ignored


A decorative image / icon must meet WCAG principles:

### 1. Perceivable

- All non-text content that is purely for decoration or which repeats existing on-screen text nearby should be ignored and skipped over by screenreaders.

## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Decorative image / icon

Decorative image / icon usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use decorative images when the image does not convey editorially relevant information.
- Use decorative images when alternative text would repeat nearby content (e.g. A shoe icon next to a Shoes heading).


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a decorative image / icon more effectively.

- Do not provide alternative text that repeats nearby content.
- Do not omit the <code class="language-plaintext highlighter-rouge">alt</code> attribute itself. This will cause screen readers to read the <code class="language-plaintext highlighter-rouge">src</code> filename. Always include a <code class="language-plaintext highlighter-rouge">src</code> attribute even if it’s empty.
- Do not expose decorative images to screen readers.
- Do not use decorative images to communicate important information or application status.


### Decorative image / icon misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a decorative image / icon. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Not every image requires descriptive alternative text.
- A lifestyle brand image is not decorative. It conveys the people, values, aspirations, or experiences associated with the brand.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16