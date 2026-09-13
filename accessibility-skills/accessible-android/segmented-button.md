---
id: accessibility-skills-android-segmented-button
title: "Segmented button"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-android/segmented-button/
---

# Android Segmented button skills



## How to test a segmented button 

Given that I am on a screen with a segmented button

### 1. Keyboard only

- WHEN I use the tab key to move focus to a segmented button

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter to activate the button
 
  - I SEE the state changes


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a button

  - I HEAR its purpose is clear and matches visible label

  - I HEAR if single select it identifies as radio button

  - I HEAR if multiple select it identifies as checkbox

  - I HEAR its visible label (if any) is grouped or associated with the button in a single swipe

  - I HEAR it expresses its state (selected/disabled)

- THEN when I doubletap with the button in focus
 
  - I HEAR the state changes


### 3. Device settings

- WHEN I use text resize I SEE this element is exempt from text resizing requirements


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13