---
id: atomica11y-skills-web-input-text
title: "Text input"
description: Code and test accessible Web Text input. Use when people enter a short text value.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/input-text/
---

[Source material](https://www.atomica11y.com/accessible-web/input-text/)

# Web Text input skills



## How to test a text input 

Given that I am on a screen with a text input

### 1. Keyboard only

- WHEN I use the tab key to move focus to a text input

  - I SEE focus is strongly visually indicated


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a text input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a text input

  - I HEAR hints or errors are read after the label, related inputs include a group name (ex: enter your personal information)

  - I HEAR if applicable, it expresses its state (required, disabled / dimmed / unavailable)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a text input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a text input

  - I HEAR hints or errors are read after the label, related inputs include a group name (ex: enter your personal information)

  - I HEAR if applicable, it expresses its state (required, disabled / dimmed / unavailable)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Text input

Text input usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a text input field to collect freeform text data from users.
- Use a text input field when the user must supply information that cannot be predetermined.
- Use a text input field when responses may vary in structure, spelling, or format.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a text input more effectively.

- Do not disable focus styles, as they are critical for accessibility.
- Do not use a text input field for predefined options; use a select dropdown or radio buttons instead.
- Do not rely on placeholder text for label or description, as it disappears when users start typing.
- Do not remove or override the semantic <code class="language-plaintext highlighter-rouge">&lt;label for&gt;</code> and <code class="language-plaintext highlighter-rouge">id</code> association with ARIA.
- Do not use Material style floating labels; instead stack labels above the text input field.
- Do not lay out text input fields across 2 column forms; instead vertically stack text input fields.
- Do not visually imply that an input accepts more characters than the maximum expected length (e.g., US ZIP Code). When the expected character count is known, the input’s visual width and size attribute MUST match that length. This aids with cognitive understanding for all people.


### Text input misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a text input. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Placeholder text cannot be used as a label; visible labels are required for accessibility.
- Autofocus does not improve user experience or accessibility; unexpected focus change will disorient screen reader and keyboard users.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16