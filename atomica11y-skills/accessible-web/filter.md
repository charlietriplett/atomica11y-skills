---
id: atomica11y-skills-web-filter
title: "Filter"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/filter/
---

[Source material](https://www.atomica11y.com/accessible-web/filter/)

# Web Filter skills



## How to test a filter 

Given that I am on a screen with a filter

### 1. Keyboard only

- WHEN I use the tab key to move focus to controls inside the filter

  - I SEE focus is strongly visually indicated

- THEN when I use the focused control
 
  - I SEE quantity and type of results updates


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to controls inside the filter

  - I HEAR each control&#39;s purpose is clear

  - I HEAR each control uses an appropriate role

  - I HEAR each control expresses its state

  - I HEAR sets of similar controls (like radio buttons) have a group name

- THEN when I use the focused control
 
  - I HEAR quantity and type of results updates


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on controls inside the filter

  - I HEAR each control&#39;s purpose is clear

  - I HEAR each control uses an appropriate role

  - I HEAR each control expresses its state

  - I HEAR sets of similar controls (like radio buttons) have a group name

- THEN when I doubletap with controls in focus
 
  - I HEAR quantity and type of results updates


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Filter

Filter usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use filters to allow users to narrow down large sets of data or search results.
- Use aria-live to dynamically announce the updated result count to screen readers when a filter is applied.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a filter more effectively.

- Do not automatically move focus to the search results when a filter is triggered.
- Do not use an aria-live region for the entire contents of results. Only use aria-live on an update a summary, like the results count.


### Filter misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a filter. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Screen reader users do not automatically know when visual content updates unless it is announced programmatically via an aria-live region.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16