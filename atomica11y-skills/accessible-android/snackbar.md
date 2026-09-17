---
id: atomica11y-skills-android-snackbar
title: "Snackbar"
description: Test accessible Android Snackbar. Use when a temporary Android status message confirms an action or reports a non-blocking event.
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-android/snackbar/
---

[Source material](https://www.atomica11y.com/accessible-android/snackbar/)

# Android Snackbar skills



## How to test a snackbar 

Given that I am on a screen with a snackbar

### 1. Keyboard only

- WHEN I use an action that opens a snackbar

  - I SEE the snackbar text

- THEN when I use the arrow keys
 
  - I SEE the snackbar can be browsed

- THEN when I use the tab key
 
  - I SEE focus moves to interactive controls in the snackbar


### 2. Android screenreader

- WHEN I use a screenreader AND I use an action that opens a snackbar

  - I HEAR the snackbar text is announced on appearing

  - I HEAR when dismissed manually, focus returns to meaningful next step

- THEN when I swipe
 
  - I HEAR focus moves to the snackbar at the end of the screen

- THEN when I swipe within a snackbar
 
  - I HEAR focus moves to interactive controls in the snackbar


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17