---
id: accessibility-skills-android-search
title: "Search"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-android/search/
---

# Android Search skills



## How to test a search 

Given that I am on a screen with a search

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a search field

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter to activate the search field
 
  - I SEE the search results are displayed


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a search field

  - I HEAR its purpose is clear and matches any visible label

  - I HEAR it identifies itself as a search field

  - I HEAR it expresses its state (disabled, etc)

- THEN when I doubletap with the search field in focus
 
  - I HEAR the keyboard is displayed


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13