---
id: atomica11y-skills-ios-tab-bar
title: "Tab bar"
description: Test accessible iOS Tab bar\". Use when people switch between primary iOS destinations.
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-ios/tab-bar/
---

[Source material](https://www.atomica11y.com/accessible-ios/tab-bar/)

# iOS Tab bar skills



## How to test a tab bar 

Given that I am on a screen with a tab bar

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to a tab

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar to activate the tab
 
  - I SEE the action occurs


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a button input

  - I HEAR its purpose is clear and matches any visible label

  - I HEAR the tab identifies itself as a tab

  - I HEAR the tab identifies its index (ex: 2 of 5)

  - I HEAR the tab expresses its state (selected)

- THEN when I doubletap with the button in focus
 
  - I HEAR the action occurs


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17