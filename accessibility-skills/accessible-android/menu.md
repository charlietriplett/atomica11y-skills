---
id: accessibility-skills-android-menu
title: "Menu"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/menu/
---

[Source material](https://www.atomica11y.com/accessible-android/menu/)

# Android Menu skills



## How to test a menu 

Given that I am on a screen with a menu

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a menu

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter
 
  - I SEE the menu opens

- THEN when I use the tab key or arrow key to move focus to an option
 
  - I SEE focus is visually indicated

- THEN when I use spacebar or enter
 
  - I SEE the option is selected

- OR when I use escape key
 
  - I SEE the menu closes, focus returns to meaningful location


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a menu or option

  - I HEAR its purpose is clear and matches visible label

  - I HEAR it identifies itself as a button

  - I HEAR any visible label is read with the button in a single swipe, icons are ignored

  - I HEAR it expresses its state (disabled, selected, etc)

- THEN when I doubletap with the button or option in focus
 
  - I HEAR the action occurs


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15