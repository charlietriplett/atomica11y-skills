---
id: atomica11y-skills-web-skip-link
title: "Skip link"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-web/skip-link/
---

[Source material](https://www.atomica11y.com/accessible-web/skip-link/)

# Web Skip link skills



## How to test a skip link 

Given that I am on a screen with a skip link

### 1. Keyboard only

- WHEN I use the tab key to move focus to a skip link

  - I SEE focus is strongly visually indicated

- THEN when I use the enter key to activate the link
 
  - I SEE my focus moves directly to the targeted element


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a skip link

  - I HEAR it describes which landmark it&#39;s targeting

  - I HEAR it identifies itself as a link

  - I HEAR it is typically the first element in the page

- THEN when I use the enter key to activate the link
 
  - I HEAR my focus moves directly to the targeted element


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to focus on a skip link

  - I HEAR it describes which landmark it&#39;s targeting

  - I HEAR it identifies itself as a link

  - I HEAR it is typically the first element in the page

- THEN when I doubletap with the link in focus
 
  - I HEAR my focus moves directly to the targeted element


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Skip link

Skip link usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a skip link to allow users to bypass repetitive navigation.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a skip link more effectively.

- Do not use a <button> for skip links. It is a link because it take the user from the top of the page to a landmark within the page.</button>


### Skip link misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a skip link. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Screen reader users are not the only people who need skip links. People who use keyboard or alternative navigation also use them.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16