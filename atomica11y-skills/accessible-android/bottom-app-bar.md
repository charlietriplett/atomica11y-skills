---
id: atomica11y-skills-android-bottom-app-bar
title: "Bottom app bar"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/bottom-app-bar/
---

[Source material](https://www.atomica11y.com/accessible-android/bottom-app-bar/)

# Android Bottom app bar skills



## How to test a bottom app bar 

Given that I am on a screen with a bottom app bar

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a button

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter to activate the button
 
  - I SEE the action occurs


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a button

  - I HEAR its purpose is clear and matches any visible label

  - I HEAR it identifies itself as a button

  - I HEAR any visible label is read with the button in a single swipe

  - I HEAR it expresses its state (disabled, selected, etc)

- THEN when I doubletap with the button in focus
 
  - I HEAR the action occurs


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15