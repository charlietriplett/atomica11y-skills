---
id: accessibility-skills-web-section-region
title: "Region section landmark"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-web/section-region/
---

# Web Region section landmark skills



## How to test a region section  

Given that I am on a screen with a region section landmark

### 1. Keyboard only

- WHEN  I use the tab key to move focus to a control in the landmark
 
  - I SEE focus moves to the control (but the landmark itself does not receive focus)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use landmark shortcuts

  - I HEAR it is discoverable as a region landmark

  - I HEAR its purpose is unique and clear

- WHEN  I use the tab key to move focus to a control in the landmark
 
  - I HEAR focus moves to the control (but the landmark itself does not receive focus)


### 3. Mobile screenreader

- WHEN I use a screenreader AND I use screen reader shortcuts 

  - I HEAR it is discoverable as a region landmark

  - I HEAR its purpose is unique and clear

- OR WHEN  I swipe to move focus to a control in the landmark
 
  - I HEAR focus moves to the control (but the landmark itself does not receive focus)


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Region section landmark

Region section landmark usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a region landmark to group significant, related content sections.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a region section landmark more effectively.

- Do not overuse the region role, which creates landmark noise for screen reader users.


### Region section landmark misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a region section landmark. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Every visual section on a page does not need to be a programmatically defined region. You can use headings to indicate page structure.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13