---
id: atomica11y-skills-web-progress
title: "Progress indicator"
description: Code and test accessible Web Progress indicator. Use when a Web task has measurable progress or an indeterminate loading state.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/progress/
---

[Source material](https://www.atomica11y.com/accessible-web/progress/)

# Web Progress indicator skills



## How to test a progress indicator 

Given that I am on a screen with a progress indicator

### 1. Keyboard only

- WHEN I use the arrow key to browse to a progress bar

  - I SEE the progress bar comes into view


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the arrow key to browse to a progress bar

  - I HEAR the progress indicator purpose is clear

  - I HEAR it identifies itself as some kind of progress indicator

  - I HEAR it expresses its current value if it dynamically changes


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to browse to a progress bar

  - I HEAR the progress indicator purpose is clear

  - I HEAR it identifies itself as some kind of progress indicator

  - I HEAR it expresses its current value if it dynamically changes


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Progress indicator

Progress indicator usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- A progress indicator answers 2 questions. What is happening? Is the system working?
- Because humans are bad at naming things, there are many things humans call progress bars and loading spinners, many of which are not a true progress indicator. They may mean an actual <code class="language-plaintext highlighter-rouge">&lt;progress&gt;</code> bar that indicates an application is working through a processs beyond user control. They may mean a navigable step-by-step control group. They may mean a non-navigable step-by-step list. They may mean a full viewport loading spinner.
- If the progress indicator is naming the current step-by-step of a multi-page process, refer to WAI-ARIA Multi-page Forms demos.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a progress indicator more effectively.

- Do not use a visual loading spinner without programmatic roles and states for people using screen readers.
- Do not use indefinite spinners that run longer than 10 seconds without a fallback status message.
- If a progress indicator overlays the entire viewport, do not allow focus or browsing of inert background content.


### Progress indicator misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a progress indicator. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- A loading spinner by itself is not a complete component. Programmatic roles are needed for people using a screen reader. Assistive technology must receive answers to the 2 questions. What is happening? Is the system working?


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17