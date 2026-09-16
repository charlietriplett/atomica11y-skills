---
id: atomica11y-skills-android-dialog-full-screen
title: "Full screen dialog"
description: Test accessible Android Full screen dialog. Use when an Android task needs a full-screen dialog.
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-android/dialog-full-screen/
---

[Source material](https://www.atomica11y.com/accessible-android/dialog-full-screen/)

# Android Full screen dialog skills



## How to test a full screen dialog 

Given that I am on a screen with a full screen dialog

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to the launch button AND THEN use spacebar to activate the button

  - I SEE the dialog opens

- THEN when I use the arrow keys
 
  - I SEE content in the dialog is browsed in meaningful order and does not leave the dialog

- THEN when I use the tab key
 
  - I SEE focus moves to interactive controls in the dialog

- OR when I use the tab key to move focus to the dismiss/close button AND THEN use the spacebar to activate the dismiss/close button
 
  - I SEE focus returns to the launch button


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus to the launch button

  - I HEAR the dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to the launch button

  - I HEAR when open, content behind the dialog remains inert

- THEN when I doubletap with the button in focus
 
  - I HEAR the dialog opens

- THEN when I swipe within the dialog
 
  - I HEAR focus stays trapped in the dialog

- THEN when I swipe to move focus to the dismiss/close button AND THEN double tap on the close button
 
  - I HEAR focus returns to the launch button


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16