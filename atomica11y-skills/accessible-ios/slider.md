---
id: atomica11y-skills-ios-slider
title: "Slider"
description: Test accessible iOS Slider\". Use when people set an Android or iOS value within a numeric range.
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-ios/slider/
---

[Source material](https://www.atomica11y.com/accessible-ios/slider/)

# iOS Slider skills



## How to test a slider 

Given that I am on a screen with a slider

### 1. Keyboard only

- WHEN I use focus moves visibly to the slider

  - I SEE focus is visually indicated (strongly if high contrast enabled)

- THEN when I use the left/right arrow keys to increase / decrease value one step
 
  - I SEE the state is changed


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to moves focus to the slider

  - I HEAR its name describes the purpose of the control and matches the visible label

  - I HEAR it identifies itself as &quot;adjustable&quot;

  - I HEAR its visible label is read with the input

  - I HEAR it expresses its current value

- THEN when I swipe up/down to increase/decrease slider value one step
 
  - I HEAR the state is changed


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16