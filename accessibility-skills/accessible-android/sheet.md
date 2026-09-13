---
id: accessibility-skills-android-sheet
title: "Sheet"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-android/sheet/
---

[Source material](https://www.atomica11y.com/accessible-android/sheet/)

# Android Sheet skills



## How to test a sheet 

Given that I am on a screen with a sheet

### 1. Keyboard only

- WHEN I use an action that opens a sheet

  - I SEE focus moves to the sheet

- THEN when I use the arrow keys
 
  - I SEE content in the sheet is browsed in meaningful order starting with the drag handle

- THEN when I use the tab key
 
  - I SEE focus moves to interactive controls in the sheet in meaningful order starting with the drag handle

- OR when I use the tab key to move focus to the drag handle
 
  - I SEE the sheet toggles between available heights


### 2. Android screenreader

- WHEN I use a screenreader AND I use an action that opens a sheet

  - I HEAR the sheet describes its purpose or title

  - I HEAR it identifies itself as a bottom sheet or side sheet

  - I HEAR when closed, focus returns to the launch button

- THEN when I swipe
 
  - I HEAR focus moves within the sheet

- THEN when I swipe within a standard sheet
 
  - I HEAR focus can leave the sheet

- THEN when I swipe within a modal sheet
 
  - I HEAR focus stays trapped in the sheet

- THEN when I swipe to move focus to the drag handle AND THEN double tap
 
  - I HEAR the sheet toggles between available heights


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13