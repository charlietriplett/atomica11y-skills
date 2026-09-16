---
id: atomica11y-skills-ios-search
title: "Search input field"
description: Test accessible iOS Search input field\". Use when people enter a query to find content.
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-ios/search/
---

[Source material](https://www.atomica11y.com/accessible-ios/search/)

# iOS Search input field skills



## How to test a search input field 

Given that I am on a screen with a search input field

### 1. Keyboard only

- WHEN I use the ctrl + tab or arrow keys to move focus to the input

  - I SEE focus is visually indicated (strongly if high contrast enabled)


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus on a search input field

  - I HEAR purpose is clear and matches visible label

  - I HEAR identifies itself as search field

  - I HEAR visible label is read with the input in focus

  - I HEAR number of suggestions is announced when typing

- THEN when I swipe to suggestions
 
  - I HEAR suggestion identifies itself as button


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16