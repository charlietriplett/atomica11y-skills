---
id: accessibility-skills-web-textarea
title: "Textarea multiline input"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/textarea/
---

[Source material](https://www.atomica11y.com/accessible-web/textarea/)

# Web Textarea multiline input skills



## How to test a textarea multiline input 

Given that I am on a screen with a textarea multiline input

### 1. Keyboard only

- WHEN I use the tab key to move focus to a textarea

  - I SEE focus is strongly visually indicated


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a textarea

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a textarea

  - I HEAR hints or errors (ex: chars remaining) are read after the label, related inputs include a group name (ex: contact us)

  - I HEAR if applicable, it expresses its state (required, disabled / dimmed / unavailable)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a textarea

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a textarea

  - I HEAR hints or errors (ex: chars remaining) are read after the label, related inputs include a group name (ex: contact us)

  - I HEAR if applicable, it expresses its state (required, disabled / dimmed / unavailable)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Textarea multiline input

Textarea multiline input usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a textarea to collect multi-line, freeform text input from users.
- Use a textarea when the expected response may include paragraphs, line breaks, or extended commentary.
- Use a textarea when the user must provide information that cannot be predetermined or constrained to a short, fixed format.
- Use a textarea when responses may vary in structure, spelling, grammar, or formatting.
- Use a textarea for open-ended responses such as comments, descriptions, explanations, or messages.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a textarea multiline input more effectively.

- Do not disable focus styles, as they are critical for accessibility.
- Do not use a textarea for predefined options; use a select dropdown or radio buttons instead.
- Do not rely on placeholder text for label or description, as it disappears when users start typing.
- Do not remove or override the semantic <code class="language-plaintext highlighter-rouge">&lt;label for=&gt;</code> and <code class="language-plaintext highlighter-rouge">id=</code> association with ARIA.
- Do not use Material style floating labels; instead stack labels above the text input field.
- Do not visually imply unlimited input if a maximum character limit exists. If a character limit is enforced, communicate it clearly visually and programmatically and ensure visual affordance aligns with expected input length.
- Do not remove the ability for users to manually resize the textarea unless there is a strong usability justification.


### Textarea multiline input misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a textarea multiline input. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Placeholder text cannot be used as a label; visible and programmatic labels are required for accessibility.
- Autofocus does not improve user experience or accessibility; unexpected focus change will disorient screen reader and keyboard users.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15