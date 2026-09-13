---
id: accessibility-skills-ios-announcement
title: "Announcement / update"
platform: ios
skill_type: component-assessment
version: 1.0.0
generated: "2026-09-13"
source: https://www.atomica11y.com/accessible-ios/announcement/
---

# iOS Announcement / update skills



## How to test an announcement / update 

Given that I am on a screen with an announcement / update

### 1. Keyboard only

- WHEN I use an action that triggers an announcement / update

  - I SEE the announcement / update appears

- THEN when I use the ctrl + tab key
 
  - I SEE nothing happens because announcements must NOT be focusable


### 2. VoiceOver screenreader

- WHEN I use a screenreader AND I perform an action that triggers an announcement / update

  - I HEAR its purpose is clear and matches visible content

  - I HEAR it has no role

- THEN when I use the the ctrl + tab key
 
  - I HEAR nothing happens because announcements must not be focusable


### 3. Device settings

- WHEN I use text resize I SEE text content can resize up to 200% without losing information


> AtomicA11y accessibility skills v1.0.0 | Generated 2026-09-13