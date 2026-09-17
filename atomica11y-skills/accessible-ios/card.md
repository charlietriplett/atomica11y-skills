---
id: atomica11y-skills-ios-card
title: "Card box"
description: Test accessible iOS Card box\". Use when related content or actions are grouped in a contained surface.
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-ios/card/
---

[Source material](https://www.atomica11y.com/accessible-ios/card/)

# iOS Card box skills



## How to test a card box 

Given that I am on a screen with a card box

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to any nested control

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar to activate the control
 
  - I SEE the control can be accessed


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to move focus to any nested control

  - I HEAR its purpose is clear and matches visible content

  - I HEAR any nested control expresses its role (card has no role)

  - I HEAR content and controls are individually readable

  - I HEAR any nested control expresses its state

- THEN when I doubletap with the control in focus
 
  - I HEAR the control can be accessed

- OR when I when I swipe to move focus to any nested heading
 
  - I HEAR the heading text and role of heading is announced


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17