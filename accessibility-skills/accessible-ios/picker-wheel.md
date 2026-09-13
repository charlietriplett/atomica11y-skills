---
id: accessibility-skills-ios-picker-wheel
title: "Picker wheel / spinner"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-ios/picker-wheel/
---

# iOS Picker wheel / spinner skills



## How to test a picker wheel / spinner 

Given that I am on a screen with a picker wheel / spinner

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to a picker

  - I SEE focus is visually indicated (strongly if high contrast enabled)

- THEN when I use the spacebar
 
  - I SEE the picker opens

- THEN when I use the arrow key
 
  - I SEE the selection changes


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a picker

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a button

  - I HEAR any visible label is read with the picker in a single swipe

  - I HEAR it expresses its value (and state if disabled/dimmed)

- THEN when I doubletap with the picker in focus
 
  - I HEAR the options are available

- THEN when I swipe and doubletap on a option
 
  - I HEAR the selection is changed


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13