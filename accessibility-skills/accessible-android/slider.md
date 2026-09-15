---
id: accessibility-skills-android-slider
title: "Slider"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/slider/
---

[Source material](https://www.atomica11y.com/accessible-android/slider/)

# Android Slider skills



## How to test a slider 

Given that I am on a screen with a slider

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a slider handle

  - I SEE focus is visually indicated

- THEN when I use the arrow keys 
 
  - I SEE the value increases or decreases by one


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a slider handle

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a slider

  - I HEAR it expresses its value

- THEN when I swipe up with the slider handle in focus
 
  - I HEAR the value increases or decreases by one


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15