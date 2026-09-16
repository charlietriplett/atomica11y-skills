---
id: atomica11y-skills-web-hint-help-error
title: "Hint, help, or error"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/hint-help-error/
---

[Source material](https://www.atomica11y.com/accessible-web/hint-help-error/)

# Web Hint, help, or error skills



## How to test a hint, help, or error 

Given that I am on a screen with a hint, help, or error

### 1. Keyboard only

- WHEN I use the tab key to move focus to an input

  - I SEE hint, help or error text meets size and contrast requirements


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to an input

  - I HEAR after the input name, role and state is read, the hint, help or error is read

  - I HEAR when it appears dynamically, an error is read automatically


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on an input

  - I HEAR after the input name, role and state is read, the hint, help or error is read

  - I HEAR when it appears dynamically, an error is read automatically


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Hint, help, or error

Hint, help, or error usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Provide programmatically linked inline hints and help text to clarify expected input formats.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a hint, help, or error more effectively.

- Do not hide hints, help or instructions inside tooltips.
- Do not place error messages above the label, as people using a screen reader will incorrectly associate them with the previous field.


### Hint, help, or error misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a hint, help, or error. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Tooltips are not a better user experience. Well-written, visible help text placed in proximity to the input field provides a superior experience for all users.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16