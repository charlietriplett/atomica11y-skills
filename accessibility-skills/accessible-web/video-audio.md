---
id: accessibility-skills-web-video-audio
title: "Video/audio player"
platform: web
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-15"
source: https://www.atomica11y.com/accessible-web/video-audio/
---

[Source material](https://www.atomica11y.com/accessible-web/video-audio/)

# Web Video/audio player skills



## How to test a video/audio player 

Given that I am on a screen with a video/audio player

### 1. Keyboard only

- WHEN I use the tab key to move focus to a control

  - I SEE focus is strongly visually indicated

- THEN when I use the spacebar and/or enter key to activate the button
 
  - I SEE the intended action occurs

- THEN when I use the arrow keys (left/right)
 
  - I SEE the media fast forwards/reverses


### 2. Desktop screenreader

- WHEN I use a desktop screenreader (NVDA, JAWS, VoiceOver) AND I use the tab key to move focus to a control

  - I HEAR the media control purpose is clear (play, pause, stop)

  - I HEAR media controls identify as button, switch, range etc.

  - I HEAR audio content never autoplays

  - I HEAR it expresses it state if applicable (pressed, expanded, disabled)

- THEN when I use the spacebar and/or enter key to activate the button
 
  - I HEAR the intended action occurs

- THEN when I use the arrow keys (left/right)
 
  - I HEAR the media fast forwards/reverses


### 3. Mobile screenreader

- WHEN I use a screenreader AND I swipe to move focus to a media control

  - I HEAR the media control purpose is clear (play, pause, stop)

  - I HEAR media controls identify as button, switch, range etc.

  - I HEAR audio content never autoplays

  - I HEAR it expresses it state if applicable (pressed, expanded, disabled)

- THEN when I doubletap with the media control in focus
 
  - I HEAR the intended action occurs


### 4. Device settings

- WHEN I use reduced motion I SEE autoplay (even of silent video) is stopped.


## Component intent and decision matrix

Data for deciding which components to use for what purposes.

### When to use a Video/audio player

Video/audio player usage guidelines provide insight into when and how to use a component effectively, ensuring that it serves its intended purpose.

- Use accessible media players with clearly labeled controls for playback (play, pause, stop)..
- Provide transcripts for audio and closed captions for video content with audio.


### Antipatterns not to use

Antipatterns are common misuses of a component that lead to poor user experience, overly complicated code and accessibility issues. Being aware of these helps you avoid them and use a video/audio player more effectively.

- Do not autoplay video or audio content.


### Video/audio player misconceptions

Commonly repeated myths or false beliefs lead to confusion or misuse of a video/audio player. Examine these myths to ensure you're using the component correctly and effectively, even when people repeat a myth as fact.

- Just because a video is silent doesn’t mean it is an exception to accessibility requirements. Even silent videos require descriptions or accessible alternatives to convey the visual information to screen reader users, and autoplaying motion can trigger vestibular disorders.


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-15