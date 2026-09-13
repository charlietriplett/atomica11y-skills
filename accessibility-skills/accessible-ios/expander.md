---
id: accessibility-skills-ios-expander
title: "Disclosure expander"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-ios/expander/
---

# iOS Disclosure expander skills



## How to test a disclosure expander 

Given that I am on a screen with a disclosure expander

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to the control

  - I SEE focus is visually indicated (strongly if high contrast enabled)

- THEN when I use the spacebar to activate the control
 
  - I SEE the content expands/collapses


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a disclosure control

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it has no role

  - I HEAR any visible label is read with the control in a single swipe

  - I HEAR it expresses its state (expanded/collapsed)

- THEN when I doubletap with the control in focus
 
  - I HEAR the content expands/collapses


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13