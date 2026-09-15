---
id: atomica11y-skills-ios-link
title: "Link"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-ios/link/
---

[Source material](https://www.atomica11y.com/accessible-ios/link/)

# iOS Link skills



## How to test a link 

Given that I am on a screen with a link

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to a link

  - I SEE focus is visually indicated (strongly if high contrast enabled)

- THEN when I use the spacebar to activate the link
 
  - I SEE the destination opens in a web browser


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a link

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a link

- THEN when I doubletap with the link in focus
 
  - I HEAR the destination opens in a web browser


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15