---
id: atomica11y-skills-android-date-picker
title: "Date picker"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/date-picker/
---

[Source material](https://www.atomica11y.com/accessible-android/date-picker/)

# Android Date picker skills



## How to test a date picker 

Given that I am on a screen with a date picker

### 1. Keyboard only

- WHEN I use the tab key to move focus to an individual control (text input, button, date)

  - I SEE focus is visually indicated

- THEN when I use spacebar or enter to activate the button
 
  - I SEE the selection is made


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on an individual control (text input, button, date)

  - I HEAR its purpose is clear and matches or extends visible label

  - I HEAR each item identifies its role (combo box for text input, button, full date for selection ex: &quot;17&quot; = &quot;monday, august 17&quot;)

  - I HEAR each component is a separately focusable item

  - I HEAR each item can expresses its state (disabled, selected, etc)

- THEN when I doubletap with the control in focus
 
  - I HEAR the selection is made


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15