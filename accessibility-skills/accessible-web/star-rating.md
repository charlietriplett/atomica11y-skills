---
id: accessibility-skills-web-star-rating
title: "Star rating input"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/star-rating/
---

[Source material](https://www.atomica11y.com/accessible-web/star-rating/)

# Web Star rating input skills



## How to test a star rating input 

Given that I am on a screen with a star rating input

### 1. Keyboard only

- WHEN I use the tab key to move focus to a radio group

  - I SEE focus is strongly visually indicated on the first unselected option or the selected option

- THEN when I use the spacebar to activate the radio button
 
  - I SEE the radio button with focus change state to selected.

- THEN when I use the arrow keys to focus radio button
 
  - I SEE the state is changed


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a radio group

  - I HEAR its label and purpose is clear

  - I HEAR it identifies itself as a radio option

  - I HEAR each option has an associated label and the radio group name

  - I HEAR it expresses its state (selected, checked, disabled)

- THEN when I use the spacebar to activate the radio button
 
  - I HEAR the radio button with focus change state to selected.

- THEN when I use the arrow keys to focus radio button
 
  - I HEAR the state is changed


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a radio button

  - I HEAR its label and purpose is clear

  - I HEAR it identifies itself as a radio option

  - I HEAR each option has an associated label and the radio group name

  - I HEAR it expresses its state (selected, checked, disabled)

- THEN when I doubletap with the radio in focus
 
  - I HEAR the state is changed


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Star rating input

Star rating input usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a star rating component to allow people to evaluate a product, experience or service.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a star rating input more effectively.

- Do not build a star rating as a set of unrelated links or standard buttons. Structure the rating functionally as a group of radio buttons wrapped in a fieldset.
- Do not rely on visual stars without providing a programmatic control for the rating value (e.g., 1 star, 2 stars).


### Star rating input misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a star rating input. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Star ratings do not require custom, complex ARIA widgets. They are best implemented semantically as a visually styled group of radio buttons.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15