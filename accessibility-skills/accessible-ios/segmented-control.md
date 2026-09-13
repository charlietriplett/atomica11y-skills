---
id: accessibility-skills-ios-segmented-control
title: "Segmented control"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-ios/segmented-control/
---

# iOS Segmented control skills



## How to test a segmented control 

Given that I am on a screen with a segmented control

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to a segmented control

  - I SEE focus is visually indicated (strongly if high contrast enabled)

- THEN when I use the arrow keys
 
  - I SEE the focus moves through the buttons

- THEN when I use the spacebar
 
  - I SEE the selection changes


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a segmented control

  - I HEAR purpose is clear and matches visible label

  - I HEAR identifies as a button

  - I HEAR visible label (if any) is grouped or associated with the button in a single swipe

  - I HEAR expresses its state (selected/disabled/dimmed)

- THEN when I doubletap with a button in focus
 
  - I HEAR the selection is changed


### 3. Device settings

- WHEN I use text resize I SEE this element is exempt from text resizing requirements

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13