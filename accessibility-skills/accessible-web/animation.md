---
id: accessibility-skills-web-animation
title: "Animation"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/animation/
---

# Web Animation skills



## How to test an animation 

Given that I am on a screen with an animation

### 1. Keyboard only

- WHEN I use tab key to move focus to the pause/play/hide controls

  - I SEE the control is strongly visibly focused

- THEN when I use the spacebar or enter key to activate the control
 
  - I SEE the intended action occurs


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use tab key to move focus to the pause/play/hide controls

  - I HEAR the control&#39;s purpose (pause/play/hide) is clear

  - I HEAR it identifies its role of button

  - I HEAR the control expresses its state if applicable (pressed, expanded)

- THEN when I use the spacebar or enter key to activate the control
 
  - I HEAR the intended action occurs


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to move focus to the pause/play/hide controls

  - I HEAR the control&#39;s purpose (pause/play/hide) is clear

  - I HEAR it identifies its role of button

  - I HEAR the control expresses its state if applicable (pressed, expanded)

- THEN when I doubletap to activate control
 
  - I HEAR the intended action occurs


### 4. Device settings

- WHEN I use reduced motion I SEE large motion, animations or effects are reduced or eliminated


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Animation

Animation usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use animations and motion sparingly and only to enhance understanding, not for decoration.
- Ensure lengthy or repeating animations automatically stop after 5 seconds or users are presented with an intuitive way to pause it.
- Change or disable animations when device Prefers Reduced Motion settings are activated.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a animation more effectively.

- Do not use animations that flash more than 3 times per second, this can make people physically ill.
- Do not use autoplaying animations that loop indefinitely without user control.
- Do not use animations that cannot be disabled when device Prefers Reduced Motion settings are activated.


### Animation misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a animation. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Animations do not always improve UX. People come to your application to solve a problem, not to be entertained. Motion should improve understanding, not distract from completing a task.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13