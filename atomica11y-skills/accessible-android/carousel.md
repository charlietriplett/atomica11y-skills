---
id: atomica11y-skills-android-carousel
title: "Carousel"
description: Test accessible Android Carousel. Use when content is presented as a sequence of slides, panels, or steps.
platform: android
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-android/carousel/
---

[Source material](https://www.atomica11y.com/accessible-android/carousel/)

# Android Carousel skills



## How to test a carousel 

Given that I am on a screen with a carousel

### 1. Keyboard only

- WHEN I use the tab key or arrow key to move focus to a slide

  - I SEE focus is visually indicated

- THEN when I use the spacebar to activate the slide
 
  - I SEE the action occurs


### 2. Android screenreader

- WHEN I use a screenreader AND I swipe to focus on a slide or control

  - I HEAR the purpose of the carousel is clear

  - I HEAR it identifies as container

  - I HEAR the purpose of the slide is clear

  - I HEAR it identifies as list item, index (ex: 3 of 5)

- THEN when I doubletap with the slide or control in focus
 
  - I HEAR the focused carousel item activates


### 3. Device settings

- WHEN I use text resize I SEE text can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17