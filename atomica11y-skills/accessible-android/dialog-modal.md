---
id: atomica11y-skills-android-dialog-modal
title: "Basic dialog"
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-android/dialog-modal/
---

[Source material](https://www.atomica11y.com/accessible-android/dialog-modal/)

# Android Basic dialog skills



## How to test a basic dialog 

Given that I am on a screen with a basic dialog

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to the launch button AND THEN use spacebar to activate the button

  - I SEE the dialog opens

- THEN when I use the arrow keys
 
  - I SEE content in the dialog is browsed in meaningful order and does not leave the dialog

- THEN when I use the tab key
 
  - I SEE focus moves to interactive controls in the dialog


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus to the launch button

  - I HEAR the dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to launch button or meaningful next step

  - I HEAR when open, content behind the dialog remains inert

- THEN when I doubletap with the button in focus
 
  - I HEAR the dialog opens

- THEN when I swipe within the dialog
 
  - I HEAR focus stays trapped in the dialog


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15