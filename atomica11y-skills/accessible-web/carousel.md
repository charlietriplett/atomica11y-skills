---
id: atomica11y-skills-web-carousel
title: "Carousel slideshow"
description: Code and test accessible Web Carousel slideshow. Use when content is presented as a sequence of slides, panels, or steps.
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-17"
source: https://www.atomica11y.com/accessible-web/carousel/
---

[Source material](https://www.atomica11y.com/accessible-web/carousel/)

# Web Carousel slideshow skills



## How to test a carousel slideshow 

Given that I am on a screen with a carousel slideshow

### 1. Keyboard only

- WHEN I use the tab key to move focus to carousel controls (forward, backward, pause/play, stop)

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar or enter key
 
  - I SEE the intended action occurs

- OR WHEN  I use the arrow keys (optional)
 
  - I SEE the slides advance or reverse


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to carousel controls (forward, backward, pause/play, stop)

  - I HEAR control name and purpose is clear

  - I HEAR control identifies itself as a button

  - I HEAR the number of slides and current position in the carousel is indicated

- THEN when I use the spacebar or enter key
 
  - I HEAR the intended action occurs

- OR WHEN  I use the arrow keys (optional)
 
  - I HEAR the slides advance or reverse


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to move focus to carousel controls (forward, backward, pause/play, stop)

  - I HEAR control name and purpose is clear

  - I HEAR control identifies itself as a button

  - I HEAR the number of slides and current position in the carousel is indicated

- THEN when I doubletap
 
  - I HEAR the intended action occurs


### 4. Device settings

- WHEN I use reduced motion I SEE carousel does not auto-advance, motion transitions are disabled


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Carousel slideshow

Carousel slideshow usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use a carousel over normal scrolling format when people can generally predict what’s in the carousel (e.g., ‘The world’s 5 tallest mountains’).
- Use a carousel for a multi-step form to help people stay on task, but only when proven effective by production multivariate testing.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a carousel slideshow more effectively.

- Do not use auto-advancing carousels without the ability to pause manually, by focus detection or mouse hover in the carousel container, or by detection of Prefers Reduced Motion device settings. Auto advancing carousels are distracting for people with attention differences, impossible to use for people using a screenreader, and potentially harmful for people with vestibular disorders.
- Do not use carousels for mission-critical content. People must be highly motivated to engage with a carousel beyond the first slide.


### Carousel slideshow misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a carousel slideshow. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Carousels are rarely the best solution. In practice they are almost always outperformed by simpler patterns.
- Carousels add cognitive friction; cognitive load is immediately increased over other patterns as the user must learn how to use it.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-17