---
id: atomica11y-skills-ios-dialog-sheet
title: "Sheet dialog"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-16"
source: https://www.atomica11y.com/accessible-ios/dialog-sheet/
---

[Source material](https://www.atomica11y.com/accessible-ios/dialog-sheet/)

# iOS Sheet dialog skills



## How to test a sheet dialog 

Given that I am on a screen with a sheet dialog

### 1. Keyboard only

- WHEN I use the arrow keys or ctrl + tab to move focus to the launch button AND THEN use spacebar to activate the button

  - I SEE the dialog opens

- THEN when I use the arrow keys
 
  - I SEE content in the dialog is browsed in meaningful order and does not leave the dialog

- THEN when I use the ctrl + tab key
 
  - I SEE focus moves to interactive controls in the modal dialog

- OR when I use the ctrl + tab key to move focus to the dismiss/close button AND THEN use the spacebar to activate the dismiss/close button
 
  - I SEE focus returns to the launch button


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I swipe to focus to the launch button

  - I HEAR the dialog describes its purpose or title on launch

  - I HEAR it identifies itself as a dialog

  - I HEAR when closed, focus returns to the launch button

  - I HEAR when open, content behind the dialog remains inert

- THEN when I doubletap with the button in focus
 
  - I HEAR the dialog opens

- THEN when I swipe within the modal dialog
 
  - I HEAR focus stays trapped in the modal dialog

- THEN when I swipe to move focus to the dismiss/close button AND THEN double tap on the close button
 
  - I HEAR focus returns to the launch button


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information

- WHEN I use increased contrast I SEE focus outline becomes high contrast


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-16