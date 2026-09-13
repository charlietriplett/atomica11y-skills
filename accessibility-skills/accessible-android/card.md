---
id: accessibility-skills-android-card
title: "Card"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-android/card/
---

[Source material](https://www.atomica11y.com/accessible-android/card/)

# Android Card skills



## How to test a card 

Given that I am on a screen with a card

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to any nested control

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar or enter to activate the control
 
  - I SEE the action occurs


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to move focus to any nested control

  - I HEAR its purpose is clear and matches visible content

  - I HEAR if non-actionable, any nested control expresses its role

  - I HEAR if directly actionable, it identifies as button or link

  - I HEAR any nested control expresses its state

- THEN when I doubletap with the control in focus
 
  - I HEAR the control can be accessed

- OR when I when I swipe to move focus to any nested heading
 
  - I HEAR the heading text and role of heading is announced


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13