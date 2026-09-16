---
id: atomica11y-skills-ios-toggle-switch
title: "Toggle switch"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-ios/toggle-switch/
---

[Source material](https://www.atomica11y.com/accessible-ios/toggle-switch/)

# iOS Toggle switch skills



## How to test a toggle switch 

Given that I am on a screen with a toggle switch

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to a switch

  - I SEE focus is visually indicated (strongly if high contrast enabled)

- THEN when I use the spacebar to activate the switch
 
  - I SEE the state is changed


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a switch input

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a switch button

  - I HEAR any visible label is read with the switch in a single swipe

  - I HEAR it expresses its state (dimmed, on/of)

- THEN when I doubletap with the switch in focus
 
  - I HEAR the state is changed


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16