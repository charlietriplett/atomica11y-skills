---
id: accessibility-skills-android-radio
title: "Radio button"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-android/radio/
---

[Source material](https://www.atomica11y.com/accessible-android/radio/)

# Android Radio button skills



## How to test a radio button 

Given that I am on a screen with a radio button

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a radio button

  - I SEE focus is visually indicated

- THEN when I use the spacebar to activate the radio button
 
  - I SEE the state is changed


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a radio button

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a radio button

  - I HEAR any visible label is read with the radio button in a single swipe

  - I HEAR it expresses its state (selected, unselected, disabled)

- THEN when I doubletap with the radio button in focus
 
  - I HEAR the state is changed


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13