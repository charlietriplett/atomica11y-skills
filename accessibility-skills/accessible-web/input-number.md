---
id: accessibility-skills-web-input-number
title: "Number input"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/input-number/
---

[Source material](https://www.atomica11y.com/accessible-web/input-number/)

# Web Number input skills



## How to test a number input 

Given that I am on a screen with a number input

### 1. Keyboard only

- WHEN I use the tab key to move focus to a number input

  - I SEE focus is strongly visually indicated

- THEN when I use the number keys
 
  - I SEE numbers are entered

- THEN when I use non-number keys
 
  - I SEE nothing is entered


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a number input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as an editable input

  - I HEAR hints or errors are read after the label, related inputs include a group name (ex: enter your personal information)

  - I HEAR if applicable, it expresses its state (required, disabled / dimmed / unavailable)

- THEN when I use the number keys
 
  - I HEAR numbers are entered

- THEN when I use non-number keys
 
  - I HEAR nothing is entered


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a number input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as an editable input

  - I HEAR hints or errors are read after the label, related inputs include a group name (ex: enter your personal information)

  - I HEAR if applicable, it expresses its state (required, disabled / dimmed / unavailable)

- THEN when I enter a number
 
  - I HEAR the numeric keypad is revealed


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Number input

Number input usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a number text input field for non-integer numeric values such as ZIP codes, postal codes, account numbers, customer numbers, tracking numbers, invoice numbers, credit card numbers or employee IDs.
- Use a number text input field to collect identifiers that consist of digits, but are not a stepped integer
- Use a number text input field when the value must be entered exactly as provided.
- Use a number text input field when leading zeros are significant.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a number input more effectively.

- Do not use <code class="language-plaintext highlighter-rouge">input type="number"</code> unless you strictly require browser-native up/down arrow incrementing, and even then, understand screen reader support is heavily fragmented.
- Do not use a number text input field for quantities, measurements, counts, or values that increment or decrement. Use a stepper pattern instead.
- Do not visually imply that an input accepts more digits than the expected length. Afford the input the width necessary to enter the expected digits.
- Do not add increment or decrement controls.
- Do not use a <code class="language-plaintext highlighter-rouge">type=number</code> input field for non-integer entries.
- Do not use <code class="language-plaintext highlighter-rouge">type=tel</code> unless the expected input is a telephone number. This indicates to browser autocomplete this is a telephone number.
- Do not use placeholder underscores to represent expected digits; the underscores will be disruptively read by the screen reader.


### Number input misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a number input. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Autofocus does not improve user experience or accessibility; unexpected focus change will disorient screen reader and keyboard users.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13