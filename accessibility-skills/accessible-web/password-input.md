---
id: accessibility-skills-web-password-input
title: "Password input"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/password-input/
---

[Source material](https://www.atomica11y.com/accessible-web/password-input/)

# Web Password input skills



## How to test a password input 

Given that I am on a screen with a password input

### 1. Keyboard only

- WHEN I use the tab key to move focus to the password input

  - I SEE focus is strongly visually indicated

- THEN when I use the tab key to move focus to the show/hide password feature
 
  - I SEE its name, role and state

- THEN when I use the show/hide password feature
 
  - I SEE the state of the password visibility (with or without characters entered)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to the password input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a text input

  - I HEAR hints or errors are read after the label (ex: password formatting)

  - I HEAR it expresses if the password is being shown and if applicable: required, disabled / dimmed / unavailable

- THEN when I use the tab key to move focus to the show/hide password feature
 
  - I HEAR its name, role and state

- THEN when I use the show/hide password feature
 
  - I HEAR the state of the password visibility (with or without characters entered)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a password input

  - I HEAR its purpose is clear

  - I HEAR it identifies itself as a text input

  - I HEAR hints or errors are read after the label (ex: password formatting)

  - I HEAR it expresses if the password is being shown and if applicable: required, disabled / dimmed / unavailable


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Password input

Password input usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a password input for secure text entry.
- Always provide a show password control to let the user show or hide the password characters.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a password input more effectively.

- Do not disable paste functionality inside the password field.
- Do not place the show password control after the input description where it might be easily missed.
- Do not use a password input for credit card numbers.


### Password input misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a password input. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Blocking paste doesn’t make forms more secure. It only forces users to type complex passwords manually, which reduces security by discouraging the use of password managers. For people using assistive technology, it is especially cumbersome. So don’t do that.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13