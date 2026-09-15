---
id: atomica11y-skills-ios-input-website
title: "Website input field"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-ios/input-website/
---

[Source material](https://www.atomica11y.com/accessible-ios/input-website/)

# iOS Website input field skills



## How to test a website input field 

Given that I am on a screen with a website input field

### 1. Keyboard only

- WHEN I use the ctrl + tab or arrow keys to move focus to the input

  - I SEE focus is visually indicated (strongly if high contrast enabled)


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the ctrl + tab or arrow keys to move focus to the input

  - I HEAR purpose is clear and matches visible label

  - I HEAR identifies itself as text field

  - I HEAR visible label and instructions are read with the input in focus

  - I HEAR if applicable, it expresses its state (required, dimmed, invalid)


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a text input

  - I HEAR purpose is clear and matches visible label

  - I HEAR identifies itself as text field

  - I HEAR visible label and instructions are read with the input in focus

  - I HEAR if applicable, it expresses its state (required, dimmed, invalid)


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15