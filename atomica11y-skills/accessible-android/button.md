---
id: atomica11y-skills-android-button
title: "Button"
description: Test accessible Android Button. Use when a control performs an action, submits a form, or changes content on the current screen.
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-android/button/
---

[Source material](https://www.atomica11y.com/accessible-android/button/)

# Android Button skills



## How to test a button 

Given that I am on a screen with a button

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a button

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter to activate the button
 
  - I SEE the action occurs


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a button

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a button or &quot;double tap to activate&quot;

  - I HEAR any visible label is read with the button in a single swipe

  - I HEAR it expresses its state (disabled, selected, etc)

- THEN when I doubletap with the button in focus
 
  - I HEAR the action occurs


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17