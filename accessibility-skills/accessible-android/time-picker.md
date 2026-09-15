---
id: accessibility-skills-android-time-picker
title: "Time picker"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/time-picker/
---

[Source material](https://www.atomica11y.com/accessible-android/time-picker/)

# Android Time picker skills



## How to test a time picker 

Given that I am on a screen with a time picker

### 1. Keyboard only

- WHEN I use the tab key to move focus to a time slot (text input, button, checkbox)

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter to activate the button
 
  - I SEE the action occurs


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a button

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies its role (text input, button, checkbox)

  - I HEAR any visible label is read with the button in a single swipe. dial selector reads selection of total (“hour 7 of 12”)

  - I HEAR it expresses its state (disabled, selected, etc)

- THEN when I doubletap with the button in focus
 
  - I HEAR the action occurs


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15