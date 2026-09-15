---
id: atomica11y-skills-android-checkbox
title: "Checkbox"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/checkbox/
---

[Source material](https://www.atomica11y.com/accessible-android/checkbox/)

# Android Checkbox skills



## How to test a checkbox 

Given that I am on a screen with a checkbox

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a checkbox

  - I SEE focus is visually indicated

- THEN when I use the spacebar or enter to activate the checkbox
 
  - I SEE the state is changed


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a checkbox input

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a checkbox

  - I HEAR any visible label is read with the checkbox in a single swipe

  - I HEAR it expresses its state (selected, unselected, disabled)

- THEN when I doubletap with the checkbox in focus
 
  - I HEAR the state is changed


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15