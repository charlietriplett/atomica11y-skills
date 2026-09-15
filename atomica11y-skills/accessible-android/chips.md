---
id: atomica11y-skills-android-chips
title: "Chips"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/chips/
---

[Source material](https://www.atomica11y.com/accessible-android/chips/)

# Android Chips skills



## How to test a chips 

Given that I am on a screen with a chips

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a chip

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter to activate the chip
 
  - I SEE the action occurs


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a chip

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a button, radio button or checkbox

  - I HEAR any visible label is read with the chip in a single swipe

  - I HEAR it expresses its state (checked, unchecked, disabled, etc)

- THEN when I doubletap with the chip in focus
 
  - I HEAR the action occurs


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15